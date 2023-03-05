# Logistic Regression from Scratch in Python

## Introduction:
Logistic regression is a popular machine learning technique used for binary classification problems. In this implementation, we demonstrate how to build a logistic regression model from scratch in Python. The model uses stochastic gradient descent (SGD) and the sigmoid function as the activation function.

## Implementation:
The model is tested on two datasets: blobs400 and moons500. The blobs400 dataset consists of two blobs of 400 samples each, while moons500 dataset consists of two interleaving half-moons of 500 samples each. The code divides the dataset into training, validation, and test sets. The training set contains 70% of the dataset, while the validation and test sets each contain 15% of the dataset. The code computes the accuracy for the test set and plots the decision boundary for each dataset.

## Usage:
To use this implementation, download or clone the repository to your local machine. The code is written in Python 3 and requires the following libraries to be installed: NumPy, Pandas, Matplotlib, and sklearn. Once you have installed these libraries, you can run the code by running the logistic_regression file. This will train the logistic regression model on the training data and output the accuracy of the model on the test data.

## Dataset:
The implementation uses two datasets: blobs400 and moons500, which are simple datasets included as files. One of them is linear and the other is non-linear.

## Results:
The logistic regression model achieved an accuracy of 95% on the test dataset for blobs400 and 81% for moons500. This is a good result for a binary classification problem, and the model was trained using a learning rate of 0.01.

![Result for blobs400](https://github.com/jonaidshianifar/Logistic-Regression-from-Scratch-in-Python/blob/main/images/bloobs400.png)
Result for blobs400
![Result for moons500](https://github.com/jonaidshianifar/Logistic-Regression-from-Scratch-in-Python/blob/main/images/moons500.png)
Result for moons500
## Conclusion:
This implementation shows how to implement logistic regression from scratch in Python using gradient descent. The model achieved good accuracy on the test dataset, which demonstrates the effectiveness of logistic regression for binary classification problems. Feel free to use this implementation as a starting point for your own machine learning projects!
