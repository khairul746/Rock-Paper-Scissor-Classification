# Rock-Paper-Scissor Classification : Convolutional Neural Networks

## Project Overview
The game of Rock-Paper-Scissors is a simple hand gesture-based game where three possible gestures (rock, paper, and scissors) are made using hand signs. This project is the final project in Dicoding DBS Foundation Coding Camp 2024: Machine Learning Developer. This project aims to leverage computer vision and deep learning to classify hand gestures. Using Convolutional Neural Networks (CNNs), a model has been trained to identify the hand gestures from images accurately.

## Data
The dataset used in this project is from Dicoding DBS Foundation Coding Camp 2024: Machine Learning Developer.

## Steps
- **Data Import** : Import the images data then convert image data to array and image label to numbers
- **Processing** :  Resize images, normalize pixel values, and apply data augmentation techniques like rotation, flipping, and scaling.
- **Define the Model** : Design a CNN architecture tailored for image classification, with layers such as convolutional, pooling, and fully connected layers.
- **Model Training** : Train the model on the dataset using techniques like callback.
- **Perfomance Evaluation** : Use metrics such as accuracy, confusion matrix, and F1-score to measure model performance.

## Results
- Models trained using convolutional neural networks achieved an accuracy of approximately 98.29%.
- The trained model successfully identifies self-uploaded images with a green background.

## Future Scope
- Extend the model to recognize additional gestures or combine it with other gesture-based games.
- Enhance real-time performance by optimizing the model for mobile or edge devices.
- Integrate gesture recognition into augmented reality (AR) or virtual reality (VR) applications.
