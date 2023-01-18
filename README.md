# Practicum Task for Cuetessa, Inc. – Predicting Valence of Pop Songs

## Objective

Valence describes the musical positiveness of a track, e.g. ranging from sad/depressed to happy/cheerful.  An automatic method of classifying the valence of pop songs is useful for playlist curation and other applications.  The aim of this task is to develop a Python-based module for the startup company Cuetessa,inc., in order to predict the valence of newly released pop songs.  

- Two approaches are to use as input: 
  - 1) the audio data (e.g., .wav files) of songs and 
  - 2) the lyrics of songs.  
 
Publicly available datasets can be used for training and testing. 

## Data Description

DEAM dataset (DEAM dataset - The MediaEval Database for Emotional Analysis of Music) consists of 1802 excerpts and full songs annotated with valence and arousal values both continuously (per-second) and over the whole song. The metadata describing the audio excerpts (their duration, genre, folksonomy tags).

- Annotations Data: The annotated [dataset](http://cvml.unige.ch/databases/emoMusic/) comes from Soleymani et al. (2013 . It consists of 45-s clips of 744 songs from the [Free Music Archive](https://freemusicarchive.org/) that span a variety of popular genres
    - Annotations are made available in csv format. There are six csv files in this database, four containing
average and standard deviation of arousal and valence continuous annotation for each song.
- Metadata: 
    - including, song title, genre and artist is also provided.


## Libraries used
- pandas
- numPy
- matplotlib
- seaborn
- sklearn
- Librosa

## Models Evaluated
- Support Vector Regressor
- RandomForestRegressor
- KNeighborsRegressor
- XGBRegressor
- CatBoostRegressor
- LGBMRegressor


