# CIFAR-10 CNN Image Classification

This project trains a Convolutional Neural Network on the CIFAR-10 dataset to classify images into 10 object categories.

---

## Project Overview
- Trains a CNN from scratch using TensorFlow and Keras
- Performs image classification on small color images
- Evaluates model accuracy on unseen test data
- Visualizes training performance and predictions

---

## Dataset
- Name: CIFAR-10
- Total images: 60,000
- Training images: 50,000
- Test images: 10,000
- Image size: 32 x 32 x 3
- Number of classes: 10

**Classes**
- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

---

## Data Preprocessing
- Pixel values normalized from 0–255 to 0–1
- Class labels converted to one hot encoded vectors
- Improves training stability and convergence

---

## Model Architecture
- Convolution layers with ReLU activation
- Batch normalization after convolutions
- Max pooling for spatial downsampling
- Dropout layers to reduce overfitting
- Fully connected dense layer
- Softmax output layer for classification

---

## Training Details
- Optimizer: Adam
- Loss function: Categorical Crossentropy
- Metric: Accuracy
- Epochs: 20
- Batch size: 128
- Validation using test dataset

---

## Output
- Training vs validation accuracy graph
- Training vs validation loss graph
- Sample predictions with actual labels
- Final test accuracy printed after training

---

## How to Run
1. Install dependencies  
   ```bash
   pip install tensorflow matplotlib numpy
