
# British Sign Language (BSL) Classification

This project implements a machine learning model to classify hand gestures from the British Sign Language (BSL) alphabet. The goal is to build a system that can recognise static sign language gestures from image data.

## Features

- Loads and processes BSL image dataset from Google Drive
- Displays random samples and performs image shape analysis
- Performs class distribution analysis
- Builds and trains a convolutional neural network (CNN) for image classification
- Evaluates model performance using accuracy, confusion matrix, and visualisation

## Technologies

- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- scikit-learn
- Google Colab

## How to Run

1. Mount your Google Drive (if using Colab) and set dataset path accordingly.
2. Install dependencies (most pre-installed in Colab).
3. Run notebook `BSL_30030295.ipynb` step-by-step.

## Dataset

The dataset consists of images representing one-hand and two-hand British Sign Language alphabet signs. Each class corresponds to a letter (e.g. A, B, C...).

## Author

Mariusz Sołtycz

---

This project was developed as part of my MSc Artificial Intelligence coursework. It applies image recognition and deep learning to human gesture classification using BSL.
