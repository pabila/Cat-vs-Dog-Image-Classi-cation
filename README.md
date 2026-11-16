Cat vs Dog Image Classification

Project Overview

This project focuses on classifying images into two categories: Cats and Dogs using Deep Learning and Convolutional Neural Networks (CNNs).

The objective is to build and compare different pretrained deep learning models and identify the model with the highest classification accuracy.

Dataset

The dataset contains approximately 24,998 cat and dog images.

Cat images

Dog images

Images were resized to 224 × 224 pixels and divided into training and validation datasets.

Technologies Used

Python

TensorFlow

Keras

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

Project Workflow

Dataset loading and exploration

Image data cleaning

Removal of corrupted images

Image preprocessing and resizing

Training and validation data splitting

Transfer learning using pretrained models

Model training and evaluation

Confusion matrix and classification report

Prediction on a sample image

Deep Learning Models

Three pretrained models were implemented and compared:

VGG16

ResNet50

EfficientNetB0

Model Performance

Model

Evaluation Accuracy

VGG16

97.24%

ResNet50

98.14%

EfficientNetB0

99.02%

Best Model

EfficientNetB0 achieved the highest evaluation accuracy of approximately 99.02% and was selected as the best-performing model.

The confusion matrix was:

[[493 4] [ 6 521]]

The model also successfully predicted a sample cat image.

Conclusion

This project demonstrates how deep learning and transfer learning can be used for image classification. Three pretrained models were evaluated, and EfficientNetB0 achieved the highest accuracy among them.

Key Learnings

Image preprocessing and data cleaning

CNN and transfer learning concepts

Working with pretrained models

Model training and evaluation

Confusion matrix and classification report

Image prediction using a trained model
