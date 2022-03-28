# Handwritten Digit Recognition Neural Networks for MNIST dataset

An implementation of multilayer neural network using keras to identify handwritten digits


## About MNIST dataset:
MNIST (Modified National Institute of Standards and Technology database) is probably one of the most popular datasets among machine learning and deep learning enthusiasts. The MNIST dataset contains 60,000 small square 28×28 pixel grayscale training images of handwritten digits from 0 to 9 and 10,000 images for testing. So, the MNIST dataset has 10 different classes.


## Steps:
* Import the libraries and load the dataset: Importing the necessary libraries, packages and MNIST dataset
* Preprocess the data
* Create the model
* Train and evaluate the Model
* Make predictions for test data
* Analyze the confusion matrix


## Installation

To install all the dependencies:

```bash
  pip3 install -r requirements.txt
```

## Deployment

Make sure you have jupyter notebook installed, if yes then inside terminal at project location, run:

```
  jupyter notebook
```

## Accuracy

It achieved 96% of accuracy using 2 hidden layers and took less than 10 secs to run.
