# DAY--11
A simple TensorFlow neural network that classifies temperature readings into Low, Medium, or High categories.
# Simple Temperature Classifier

## Objective

Train a small TensorFlow neural network to classify temperature readings into three categories:

- Low
- Medium
- High

## Technologies Used

- Python
- TensorFlow
- NumPy
- Google Colab

## Temperature Categories

| Temperature | Category |
|---|---|
| 10°C – 18°C | Low |
| 20°C – 28°C | Medium |
| 30°C – 38°C | High |

## Model

A simple neural network with Dense layers and Softmax activation is used for classification.

The model is trained using:

- Optimizer: Adam
- Loss: Sparse Categorical Crossentropy
- Epochs: 500

## Test

The model is tested using:

13°C, 21°C, 28°C and 33°C.

## Result

The model classifies the temperature readings into Low, Medium, and High categories.

## Platform

Google Colab
