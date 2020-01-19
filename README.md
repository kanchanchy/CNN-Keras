# Convolutional Neural Network (CNN) using Keras
This repository implements a convolutional neural network (CNN) model using Keras framework. After that, it perfroms training and testing on CNN model for classifying MNIST dataset.

The CNN used here consists of two convolution layers. Each convolution layer is followed by a pooling layer. Two convolution layers has filters of size 3x3 and 2x2 respectively. Both pooling layers perform max pooling with filters 2x2. Covolution and pooling layers are followed by three fully connected layers where the last fully connected layer is the output layer. Relu activation is applied to each convolution and fully connected layer except the output layer (last fully connected layer), softmax activation is applied.
