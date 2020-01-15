# Face-detection-and-face-recognition

## OVERVIEW - FACE DETECTION
The face detection script is built through opencv. The opencv has haar cascades. You just have to select the suitable haar cascade and then build the bounding box coordinates for the detected face.

## HOW TO RUN

Just input the filepath of the image on which the face to be detected and then run the script in jupyter notebook.

## OVERVIEW - FACE RECOGNITION

The face recognition script is also built upon the concept of haar cascades but it works in looping all the frames of a video as a single image. First you have to train and then you'll have to predict. By making seperate folders for every class and their respective images,You can identify it through them. 

## HOW TO RUN
1. python faces_train.py
2. python face_recognition.py
