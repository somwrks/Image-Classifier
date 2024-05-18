# Image Classifier

This project focuses on building an image classifier using Convolutional Neural Networks (CNN) to classify images into two categories: 'happy' and 'sad'. The project is implemented using TensorFlow and Keras.

## Overview

The project consists of the following components:

1. `main.ipynb`: This Jupyter Notebook file contains the main codebase for building, training, and evaluating the image classifier model.

## Dataset

The dataset used in this project is located in the `data` directory, which contains two subdirectories:

- `happy`: Contains images of happy people.
- `sad`: Contains images of sad people.

## Dependencies

The project requires the following dependencies:

- TensorFlow (version >= 2.x)
- Keras
- OpenCV
- Matplotlib
- NumPy
- Pandas

## Usage

1. Ensure all dependencies are installed.
2. Open and run the `main.ipynb` notebook in a Jupyter environment.
3. Follow the instructions and code comments within the notebook to preprocess the data, build the model, train, evaluate, and make predictions.

## Code Structure

The key components of the code include:

- Data preprocessing and loading using OpenCV and TensorFlow Datasets.
- Building the CNN model using Keras.
- Training the model using TensorFlow's `fit` method.
- Monitoring the training progress using TensorBoard callbacks.
- Evaluating the model's performance using metrics like accuracy, precision, and recall.
- Making predictions on new images.
- Saving and loading the trained model.

## Folder Structure

- `data`: Contains the image dataset.
  - `happy`: Images of happy people.
  - `sad`: Images of sad people.
- `logs`: Directory for storing TensorBoard logs during training.
- `models`: Directory for storing trained models.
  - `imageclassifier.h5`: The trained image classifier model.

## How to Contribute

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to create issues or pull requests.

## License

This project is licensed under the MIT License. Feel free to modify and distribute the code as per the terms of the license.
