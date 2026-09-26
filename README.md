# ML Algorithms from Scratch

Implementations of basic machine learning algorithms from scratch using Python and NumPy. This repository contains coursework implementations focused on understanding the underlying optimization and loss functions rather than relying on built-in model training methods.

## Projects

### Linear Regression

* Implemented linear regression using gradient descent
* Implemented Mean Squared Error (MSE) and Mean Absolute Error (MAE)
* Compared the manual MSE implementation with `sklearn`'s `LinearRegression`

### Perceptron and SVM

* Implemented Perceptron Loss and Hinge Loss
* Implemented subgradient descent for both losses
* Trained both models on a binary `make_blobs` dataset
* Compared their learned parameters, loss, accuracy, and decision boundaries

## Technologies

* Python
* NumPy
* Matplotlib
* scikit-learn

## Structure

```text
ml-algorithms-from-scratch/
├── linear_regression/
│   └── linear_regression.ipynb
├── svm_perceptron/
│   └── svm_perceptron.ipynb
├── README.md
```
