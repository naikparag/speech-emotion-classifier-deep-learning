# speech-emotion-classifier-deep-learning
Human speech emotion classifier using DNN

DATASET:
- "The Ryerson Audio-Visual Database of Emotional Speech and Song (RAVDESS)" by Livingstone & Russo is licensed under CC BY-NA-SC 4.0.
- https://zenodo.org/record/1188976#.XME5AZMzbUI

REFERENCE:
- https://github.com/MITESHPUTHRANNEU/Speech-Emotion-Analyzer
- https://github.com/harry-7/speech-emotion-recognition
- Microsoft Research: Automatic Speech Recognition - https://www.youtube.com/watch?v=q67z7PTGRi8
- https://librosa.github.io/librosa/generated/librosa.feature.mfcc.html

SETUP (MAC):
```
docker run --name tf2notebook -d -p 8800:8888 -v  <local machine folder here>:/home/jovyan/work jupyter/datascience-notebook
docker exec -it tf2notebook pip install --upgrade pip
docker exec -it tf2notebook pip install tensorflow==2.0.0-alpha0
docker exec -it tf2notebook pip install librosa
```
