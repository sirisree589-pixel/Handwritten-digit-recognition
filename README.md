AI-Based Handwritten Digit Recognition using PyTorch
Project Overview

This project uses a Multilayer Feed-Forward Neural Network to recognize handwritten digits (0–9) from the MNIST dataset.

Technologies Used
Python
PyTorch
Torchvision
NumPy
Matplotlib
Seaborn
Scikit-learn
Dataset

The MNIST dataset contains 70,000 grayscale images of handwritten digits, each of size 28 × 28 pixels.

Training: 60,000 images
Testing: 10,000 images
Classes: 10 digits (0–9)
Model Architecture

The model is a fully connected neural network with:

Input layer: 784 features
Hidden layers: 512, 256, and 128 neurons
Activation function: ReLU
Regularization: Dropout and Batch Normalization
Output layer: 10 classes
Features
MNIST dataset loading and preprocessing
Training and validation
Model evaluation and accuracy calculation
Classification report and confusion matrix
Training performance visualization
Sample digit predictions
Hidden-layer experiment
Model saving
How to Run
Open Google Colab.
Create a new notebook.
Select a GPU runtime if available.
Copy the project code into a cell.
Run the cell.

The dataset downloads automatically.

Output

The project displays training and validation metrics, test accuracy, a classification report, a confusion matrix, and sample predictions.

The trained model is saved as mnist_classifier.pth.

Author

B.DIVYA SREE
