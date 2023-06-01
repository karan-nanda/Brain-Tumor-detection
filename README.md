# Brain-Tumor-detection
## Brain Tumor Detection Model

This repository contains code for a deep learning model that detects brain tumors in MRI images. The model is implemented using a fine-tuned ResNet-50 architecture and trained on a dataset of 5,712 images, including Glioma, Meningioma, Pituitary, and Normal classes.

## Dataset
The dataset used for training the model consists of 1,321 images of Glioma, 1,339 images of Meningioma, 1,457 images of Pituitary tumors, and 1,595 images of normal/healthy brains. The images are in the MRI format and have been preprocessed for training the model. Dataset for both training and testing can be found [here](https://drive.google.com/drive/folders/19YA1DXAZiNXMzBS0uJPkmVdIfSxMXgTE?usp=sharing)

## Model Architecture
The brain tumor detection model utilizes a fine-tuned ResNet-50 architecture. ResNet-50 is a deep convolutional neural network that has been pretrained on a large dataset and has shown excellent performance in various computer vision tasks.

## Dependencies
The implementation of the model is done in Python using the TensorFlow framework. Ensure that you have the following dependencies installed:

Python 3.x
TensorFlow
Other necessary libraries (NumPy, Pandas, Matplotlib, etc.)

## Results

The model has been trained to achieve high accuracy in classifying brain MRI images into different tumor types and normal/healthy categories. The accuracy and performance of the model can be evaluated by testing it on an independent test dataset or real-world MRI images.

