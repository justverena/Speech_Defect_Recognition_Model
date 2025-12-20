# Introduction

## 1. Project Objective
#### The goal of this project is to develop a model capable of automatically classifying speech defects from short audio samples.  

The initial prototype focuses on binary classification of:
- **normal speech**
- **articulation disorders** (e.g., mispronunciations, phonetic deviations)
- **stuttering**, (CLASS / SEP-28k).  

## 2. Datasets Used

For this project we rely on two primary sources:

### 1. Articulation Disorders Dataset  
Contains recordings of subjects with various articulation impairments.  
Directory example:

`dataset_raw/articulation/M05/Session1/wav_arrayMic/0001.wav`

### 2. Normal Speech Dataset (LibriSpeech Subset)
Contains clean speech samples from speakers without speech impairments.  
Directory example:

`dataset_raw/normal/dev-clean/batch1/1993/147964/1993-147964-0000.wav`

### 3. Stuttering Speech: SEP-28k dataset
Capturing temporal irregularities and disfluencies.
Each dataset had its own format and structure.

Directory example:

`dataset_raw/stuttering/WomenWhoStutter/WomenWhoStutter_97_15.wav`