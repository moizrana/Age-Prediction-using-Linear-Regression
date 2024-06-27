# Speaker Age Prediction from Audio Recordings

The **Speaker Age Prediction from Audio Recordings** project aims to predict the age of speakers based on acoustic features extracted from their audio recordings. This documentation provides an overview of the project, including its purpose, methodology, and implementation details.

## Overview

This project utilizes machine learning techniques to predict the age of speakers from audio recordings. The workflow involves several key steps:

1. **Data Collection**: Audio recordings of speakers with associated age labels are collected for training and testing the model.
2. **Feature Extraction**: Relevant acoustic features such as pitch, intensity, duration, spectral centroid, and others are extracted from the audio recordings.
3. **Data Preprocessing**: The extracted features are preprocessed to handle missing values, normalize data, and prepare it for model training.
4. **Model Training**: A linear regression model is trained using the preprocessed data to predict speaker age based on the extracted features.
5. **Model Evaluation**: The trained model is evaluated using various metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared (R2) coefficient of determination.

## Methodology

The project's code is implemented in Python using popular libraries such as NumPy, pandas, librosa, and scikit-learn. The main components of the code include:

- **Data Loading and Cleaning**: Audio data is loaded from CSV files and cleaned to remove duplicates and handle missing values.
- **Feature Extraction**: Acoustic features are extracted from audio recordings using the librosa library.
- **Model Training**: A linear regression model is trained using gradient descent optimization.
- **Model Evaluation**: The trained model is evaluated using standard regression metrics to assess its performance.

## Implementation Details

### Data Collection

Audio recordings are collected, each associated with an age label. These recordings serve as the dataset for training and testing the model.

### Feature Extraction

Using the `librosa` library, various acoustic features are extracted from the audio recordings. These features include:

- Pitch
- Intensity
- Duration
- Spectral Centroid
- And others

### Data Preprocessing

The extracted features are preprocessed to handle missing values and normalize the data. This step ensures that the data is in a suitable format for model training.

### Model Training

A linear regression model is trained using the preprocessed data. Gradient descent optimization is employed to minimize the error and improve the accuracy of the predictions.

### Model Evaluation

The performance of the trained model is evaluated using various regression metrics:

- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **R-squared (R2) coefficient of determination**

## Getting Started

### Prerequisites

- Python 3.x
- NumPy
- pandas
- librosa
- scikit-learn
