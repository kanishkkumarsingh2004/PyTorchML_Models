# MNIST Classifier with PyTorch

This project implements a simple neural network to classify handwritten digits using the MNIST dataset. It utilizes PyTorch for building and training the model and visualizes the training process using Matplotlib.

## Project Description

This project demonstrates how to build and train a neural network to classify images from the MNIST dataset. The MNIST dataset contains 70,000 28x28 grayscale images of handwritten digits (0-9). We use a simple feed-forward neural network with three layers. The model is trained using stochastic gradient descent (SGD) with CrossEntropy loss. 

### Features
- **Model**: A simple fully connected neural network with three layers.
- **Training**: The model is trained using the MNIST training dataset.
- **Testing**: The model is tested on the MNIST test dataset to evaluate accuracy.
- **Visualization**: The loss and accuracy are plotted during the training process.
  
## Installation

To run the project, you'll need to have Python installed along with the following libraries:

- torch
- torchvision
- matplotlib

You can install the required libraries using the following command:

```bash
pip install torch torchvision matplotlib
