Dog vs Cat Classification using CNN
 Project Overview

This project is a binary image classification system that uses a Convolutional Neural Network (CNN) to identify whether an input image contains a dog or a cat.

The model is trained on labeled images of dogs and cats and learns visual features such as edges, shapes, and textures to make predictions on new, unseen images.

Objective

To understand how CNNs work for image classification

To train a deep learning model that can distinguish between dogs and cats

To perform real-time prediction on a single image

Model Architecture (High Level)

The CNN consists of:

Convolutional layers – extract image features

MaxPooling layers – reduce image size and computation

Flatten layer – convert 2D features into 1D

Dense layers – learn decision boundaries

Sigmoid output layer – binary classification (Dog / Cat)

Dataset Structure

The dataset must be organized in the following format:

dataset/
│
├── train/
│   ├── dogs/
│   │   ├── dog1.jpg
│   │   └── dog2.jpg
│   │
│   └── cats/
│       ├── cat1.jpg
│       └── cat2.jpg
│
├── validation/
│   ├── dogs/
│   └── cats/
│
└── image.png   # image used for prediction

Predict an Image

Place an image named image.png in the same folder and run the prediction code.

The model will output:

Dog or Cat