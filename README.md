# Digits classification using neural nets and Keras

### Introduction 
The goal with this repo is to train a image classification model using Keras and neural nets

### How to get going: 
1. run 'poetry install'
2. activate the virtual environment run 'source path_to_venv/bin/activate'
3. poetry run python the_script_you_want_to_run.py

### Problem formulation
We have input data of handwritten digits, the MNIST dataset, and we want to predict the actual digit {0,1,2,3,4,5,6,7,8,9}. 

Hence, the problem can be written as x -> f(x) -> y, 
where x is the input data, f(x) the neural network we are going to build and y is the predicted output digit. 

input data: MNIST, an array of numbers, where each number represents a certain pixel intensity
output data: {0,1,2,3,4,5,6,7,8,9}

note: source https://www.youtube.com/watch?v=BfCPxoYCgo0