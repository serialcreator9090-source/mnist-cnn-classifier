# MNIST Handwritten Digit Classification using PyTorch

## Overview
This project explores handwritten digit classification using two deep learning approaches: a fully connected neural network and a Convolutional Neural Network (CNN).

The project covers data loading, model architecture, training, evaluation, prediction visualization, and confusion matrix analysis.

## Models Implemented

### 1. Fully Connected Neural Network
- Implemented using PyTorch.
- Trained on the scikit-learn Digits dataset (8×8 images).
- Test accuracy: 94.72.

### 2. Convolutional Neural Network (CNN)
- Implemented using PyTorch and torchvision.
- Trained on the MNIST dataset (28×28 grayscale images).
- Architecture: Convolution → ReLU → Max Pooling → Flatten → Fully Connected Layers.
- Test accuracy: 98.61% (9,861 out of 10,000 test images).

*Note: The two models use different datasets, so their accuracy scores are not a direct comparison.*

## Technologies
- Python
- PyTorch
- torchvision
- NumPy
- Matplotlib
- scikit-learn

## Key Concepts Learned
- Neural network architecture and forward propagation
- Loss functions and backpropagation
- Adam optimizer and model training
- Convolution, activation, and max pooling
- Training versus evaluation mode
- Test accuracy, prediction visualization, and confusion matrices

## How to Run
1. Clone or download this repository.
2. Install the required libraries:

   `pip install torch torchvision numpy matplotlib scikit-learn jupyterlab`

3. Open `mnist_cnn_classifier.ipynb` in JupyterLab.
4. Run the notebook cells from top to bottom.

## Future Improvements
- Compare both approaches on the same dataset.
- Analyze incorrectly classified images.
- Experiment with CNN architecture and hyperparameters.
- Explore real-time handwritten digit recognition.

## Project Status
Completed learning project.
