# Emotional-classification-through-voice-using-Backpropagation
Simple neural net to classify the emotion in an audio


# Topic
In this notebook I experienced with audio classification, the dataset has 1400 audios of spoken sentences in each of the 7 emotional states (happy, angry, pleasant, disgust, sad, 
neutral and fear). My goal is to preprocess the raw audio into a form that a neural network can learn from, for that I used Melspectrograms, and them build a model that can accurately
classify a voice tone as being in one of the mentioned class.


# Objectives
- Process raw audio data to be neural net ready
- Build a classififer that can tell the emotion in a voice

# Summary

- Extracting audio files
- Extracting Mel Spectrograms
- Audio transformation
- Creating the target dataset
- Train/Test split
- Creating the data loaders
- Building the Classifier
- Training and inference
- Trying out the model
- Conclusion


# Libraries
- Pandas
- Nmupy
- Torchaudio
- Librosa
- Iphython
- Sklearn
- Glob

# Datasource
https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess?fbclid=IwAR181U1jADr4HCc591qJb61d0OjZXHZ5PV-iAi7sEnn-tLJQ2vaHTcce4Qk
