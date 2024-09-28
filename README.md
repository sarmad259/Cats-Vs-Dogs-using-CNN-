# Cats vs Dogs Image Classifier

## Project Overview
This project is a Convolutional Neural Network (CNN) based image classifier built with TensorFlow and Keras. It is designed to classify images as either cats or dogs using a dataset of labeled images. The model is trained on a subset of images and evaluated on separate validation and test sets to ensure accurate classification.

## Overview
The goal of this project is to distinguish between images of cats and dogs. The dataset is split into training, validation, and test sets to train and evaluate the model. The model leverages deep learning techniques, utilizing convolutional layers to extract features and a dense layer to classify the images into binary categories (cat or dog).

## Key Points
- **Deep Learning Techniques:** Utilizes CNN architecture for feature extraction.
- **Data Split:** Training, validation, and test sets for model development and evaluation.
- **Image Augmentation:** Used to enhance model generalization on unseen data.

## Training Process
Training the model involves:

1. **Image Augmentation:** Enhances the dataset to improve the model's generalization ability.
2. **Convolutional Layers:** A series of convolutional layers progressively extracts visual features from the images.
3. **Dense Layer:** A final dense layer classifies the images as either cat or dog.

The result is a model that can accurately classify new images of cats and dogs with a high degree of accuracy.
