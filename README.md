Cat and Dog Image Classification using CNN and Keras

## Project Overview

This project demonstrates an image classification model built using Convolutional Neural Networks (CNN) and Keras. The model is trained to distinguish between images of cats and dogs.

## Features

- Utilizes a CNN architecture for image classification
- Trained on a dataset of cat and dog images
- Achieves high accuracy in distinguishing between the two classes

## Dataset

The dataset used for this project contains images of cats and dogs. It can be downloaded from [Kaggle](https://www.kaggle.com/c/dogs-vs-cats/data).

## Model Architecture

The model architecture consists of the following layers:

1. **Convolutional Layer:** 32 filters, kernel size of 3x3, ReLU activation, input shape of (100, 100, 3)
2. **Max-Pooling Layer:** pool size of 2x2
3. **Convolutional Layer:** 32 filters, kernel size of 3x3, ReLU activation
4. **Max-Pooling Layer:** pool size of 2x2
5. **Flatten Layer:** flattens the input
6. **Fully Connected (Dense) Layer:** 64 units, ReLU activation
7. **Output Layer:** 1 unit, sigmoid activation (for binary classification)
