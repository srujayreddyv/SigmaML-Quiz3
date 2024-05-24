# SigmaML Quiz 3 - Srujay

This project involves creating an Artificial Neural Network (ANN) with 4 hidden layers to solve the classification problem on the "Fashion MNIST" Dataset. It also includes an ablation study to analyze the effect of varying the number of hidden layers and neurons per layer on the model's accuracy.

## Dataset

The dataset used is the Fashion MNIST dataset, available from [TensorFlow Datasets](https://www.tensorflow.org/api_docs/python/tf/keras/datasets/fashion_mnist/load_data).

## Requirements

- Use TensorBoard to log training/test data (both scalars and images).
- Perform an ablation study:
  - Analyze accuracy changes with varying hidden layers.
  - Analyze accuracy changes with varying neurons per layer.

### Prerequisites

- Python 3.x
- TensorFlow
- Matplotlib
- Seaborn
- NumPy
- scikit-learn

## Script Overview

### Imports and Supporting Functions

- Imports necessary libraries.
- Defines a function to plot sample images from the dataset.

### Data Exploration

- Loads the Fashion MNIST dataset.
- Defines class names.
- Plots sample images.

### Data Pre-processing

- Normalizes the data.
- Reshapes the data to add a channel dimension.

### Model Building and Training

- Defines and compiles the original model with 4 hidden layers.
- Defines and compiles the model with 3 hidden layers.
- Defines and compiles the model with fewer neurons per layer.
- Trains all models and logs training details using TensorBoard.

### Evaluation

- Evaluates each model.
- Generates classification reports.
- Generates and plots confusion matrices.
- Plots training and validation accuracy and loss.

### Viewing TensorBoard

- Uses TensorBoard to visualize the training logs for all models.

##License
This project is licensed under the Apache License 2.0. See the LICENSE file for details.
