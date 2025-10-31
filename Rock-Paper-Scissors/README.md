
# Dogs vs Cats Classifier 🐱🐶

A convolutional neural network (CNN) that classifies images of cats and dogs with high accuracy using TensorFlow and Keras.

## Overview

This project implements a deep learning solution for image classification, distinguishing between cats and dogs in images. The model achieves **70%+ accuracy** through advanced CNN architecture, data augmentation, and transfer learning techniques.

## Features

- **CNN Architecture**: Custom neural network with multiple convolutional and pooling layers
- **Data Augmentation**: Real-time image transformations to prevent overfitting
- **Transfer Learning**: Optional MobileNetV2 integration for improved performance
- **Visualization**: Training history and prediction results plotting
- **Model Evaluation**: Comprehensive metrics and performance analysis

## Tech Stack

- **TensorFlow 2.x** & **Keras**
- **Python 3**
- **OpenCV** (image processing)
- **Matplotlib** (visualization)
- **NumPy** (numerical operations)

## Dataset

The model uses the standard Cats vs Dogs dataset from Kaggle, containing:
- 2,000 training images (1,000 cats + 1,000 dogs)
- 1,000 validation images
- 50 test images

# Install dependencies
pip install tensorflow matplotlib numpy pandas opencv-python
