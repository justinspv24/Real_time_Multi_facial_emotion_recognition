# Real-time Multi-facial Emotion Recognition

This repository contains the code for a real-time multi-facial emotion recognition system. The system uses YOLOv5 for real-time face detection and a customized Convolutional Neural Network (CNN) for emotion classification.

## Overview
The project aims to recognize multiple facial emotions in real-time. It can detect faces in a video stream and classify each face into one of the seven emotion classes: angry, disgust, fear, happy, neutral, sad, and surprise.

## Dataset
The model was trained on the FER2013 dataset, which contains 35,887 grayscale images of faces, each labeled with one of the seven emotions.

### Face Detection
- **YOLOv5**: Used for real-time face detection.

### Emotion Classification
- **Customized CNN**: A convolutional neural network designed specifically for this task.
- **Classes**: The model classifies faces into the following seven emotions:
  - Angry
  - Disgust
  - Fear
  - Happy
  - Neutral
  - Sad
  - Surprise

## Training
- **Epochs**: 120
- **Optimizer**: Adam
- **Learning Rate**: \(10^{-4}\)
- **Loss Function**: Categorical Cross Entropy


