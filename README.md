# Emotion and Gender Detection in Video using DeepFace

## Project Overview

The project detects faces, emotions and predicting gender from faces in a video using the `DeepFace` library. 

The video is processed frame by frame, with each detected face outlined with a green rectangle. The dominant emotion and predicted gender are annotated on the video in lilac text.

## Features

- **Face Detection**: Detects faces in each frame of the video.
- **Emotion Detection**: Identifies the dominant emotion for each detected face.
- **Gender Prediction**: Predicts the gender of each detected face.

## Outcome

**Mixed success**: 
-	The main face is detected properly when there is a single person in the frame, however, there are small "ghosts" around (funny how men's ties are detected as faces).
-	When there are a bunch of people in the frame, the gender and emotions of each person are detected with low accuracy.

Exciting to see the parliamentary debate video packed with emotions!

![](emoji.jpg)
