# SERP
SPEECH EMOTION REGCONITION

The idea behind creating this project was to build a machine learning model that could detect emotions from the speech we have with each other all the time. Nowadays personalization is something that is needed in all the things we experience every day. So why not have an emotion detector that will gauge your emotions and in the future recommend you different things based on your mood. This can be used by multiple industries to offer different services like marketing company suggesting you to buy products based on your emotions, automotive industry can detect the person’s emotions and adjust the speed of autonomous cars as required to avoid any collisions etc.

Environments:
     Python 3.10.4(pychram idle)
     
Dataset:
      RAVDESS: This dataset includes around 1500 audio file input from 24 different actors. 12 male and 12 female where these actors record short audios in 8 different emotions i.e. 1 = neutral, 2 = calm, 3 = happy, 4 = sad, 5 = angry, 6 = fearful, 7 = disgust, 8 = surprised. Each audio file is named in such a way that the 7th character is consistent with the different emotions that they represent.
      
Modules:
      Librosa
      Sklearn
      Soundfile
      Mathplotlib
      Numpy
      Pickle
      Glob
      Os
      Pyaudio
      STREAMLIT

ALGORITHM USED:
       MLP Classifier

EXTRACTED FEATURES:
       MFCC
       MEL SPECTROMETER
       TONNETZ
       
