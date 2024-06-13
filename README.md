# Neural Network with NumPy

This repository contains a basic neural network for classifying handwritten digits from the MNIST dataset. The network is built from scratch using NumPy, demonstrating core concepts like forward and backward propagation and gradient descent optimization.

## Features

- Two-layer neural network
- ReLU activation for the hidden layer
- Softmax activation for the output layer
- One-hot encoding for labels
- Gradient descent for optimization
- Training and evaluation on the MNIST dataset

## Usage

1. Download the MNIST dataset in CSV format from [Kaggle](https://www.kaggle.com/datasets/oddrationale/mnist-in-csv).
2. Ensure `mnist_train.csv` and `mnist_test.csv` are in the project directory.
3. Open and run `NeuralNetwork_numpy.ipynb` to train and evaluate the neural network.

## Notebook Contents

- **Data Loading**: Loads MNIST dataset.
- **Model Initialization**: Initializes weights and biases.
- **Activation Functions**: Implements ReLU and softmax functions.
- **Forward Propagation**: Calculates layer activations.
- **Backward Propagation**: Computes gradients.
- **Parameter Updates**: Updates weights and biases using gradient descent.
- **Training**: Trains the model on the training set.
- **Evaluation**: Evaluates model accuracy on the test set.

## Contributing

Contributions are welcome! Feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.
