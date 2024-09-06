# Sarcasm Detection Model
(This project has been done as a programing assignment for course "Natural Language Processing in Tensorflow" in Coursera.org website.
This repository contains a machine learning model for detecting sarcasm in news headlines using deep learning techniques. The model is built with TensorFlow and Keras and employs an LSTM-based architecture.

## Files

The repository includes the following files:

- `sarcasm.json`: Dataset containing news headlines and sarcasm labels.
- `preprocessing.ipynb`: Jupyter notebook for data preprocessing and preparation.
- `README.md`: This file providing an overview of the project.

## Dataset

The dataset used for training and testing the model is `sarcasm.json`, which consists of news headlines and corresponding sarcasm labels.

## Model

The model is a Sequential neural network with the following architecture:

- **Embedding Layer**: Converts integer sequences into dense vectors.
- **Bidirectional LSTM Layer**: Captures context from both directions in the sequence.
- **Dropout Layer**: Regularization to prevent overfitting.
- **Dense Layer**: Fully connected layer with ReLU activation.
- **Output Layer**: Dense layer with sigmoid activation for binary classification.

## Training

The model is trained with the following parameters:

- **Number of Epochs**: 10
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Metrics**: Accuracy
