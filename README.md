# Fashion-MNIST Image Classification

A beginner-level deep learning project using PyTorch to classify Fashion-MNIST images into 10 different clothing categories.

## About

In this project, a simple neural network is built and trained using the Fashion-MNIST dataset.

The project covers the basic steps of a deep learning workflow:

- Loading the dataset
- Displaying the data
- Splitting data into training and testing sets
- Normalizing pixel values
- Building a neural network
- Training the model
- Making predictions
- Evaluating the model

## Model Architecture

```text
Input (784)
     ↓
Linear (128)
     ↓
ReLU
     ↓
Linear (64)
     ↓
ReLU
     ↓
Linear (10)
     ↓
Softmax
     ↓
Output
