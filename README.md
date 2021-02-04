# Dog Breed Identification

## Problem 

Identifying the breed of the dog given an image of dog

## Concept used
* Transfer Learning (MobileNetV2)
* Tensorflow
* Keras
* Neural Networks
* Pandas
* Numpy
* Matplotlib

## Data

The data we are using it from Kaggle's dog breed identification competition.<br>
https://www.kaggle.com/c/dog-breed-identification/data

## Evaluation

The evaluation is a file with prediction probabilities for each dog breed of each test image<br>
https://www.kaggle.com/c/dog-breed-identification/overview/evaluation

## Features
Some inforamation about the data:- 

* We are dealing with images(unstructured data) so it's probably  best we use deep learning or transfer learning
* There are 120 breeds of dogs (this means there are 120 different classes)
* There are 10,000+ images in training set (these images have labels)
* There are 10,000+ images in test set (we have to predict it)

## Approach
**Trained the model using MobileNetV2 <br>
Multi-class classification (used Softmax activation function and Categorical Crossentropy Loss function)**

For each operation implemented functional oriented approach :-
* Preprocessing images
* Turning data to tensors
* Turning data to batches
* Prediction probability to labels
* Creating callbacks 
* Building Model etc.

**Reaching accuracy of 99.82% on training set and loss at 0.0177**<br>
**On submitting prediction of test set, Loss ( Multi Class Log Loss ) of 0.83147 was achieved.**

## Visualising the data with true label
![data](https://user-images.githubusercontent.com/67990422/106853685-1b338200-66e0-11eb-8e1d-0306eb739519.png)

## Custom Image prediction
Prediction of Breed of dog given an image of dog<br>
![prediction](https://user-images.githubusercontent.com/67990422/106852383-fb02c380-66dd-11eb-9ea7-d63a13aa006c.png)



