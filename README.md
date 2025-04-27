# Earthquake Detection using Machine Learning

This project aims to develop a machine learning model capable of detecting earthquakes based on seismic signal data. It covers the full workflow from data ingestion and preprocessing to model training, evaluation, and prediction.

The model analyzes time-series seismic data to predict earthquake occurrences, helping to enhance early warning systems and potentially save lives.


## Project Overview

Earthquake detection is critical for disaster prevention and management. In this project, we use machine learning algorithms to identify seismic activities based on raw seismic signals. 

The notebook (`earthquake-detection.ipynb`) guides you through:
- Data loading and exploration
- Signal preprocessing and feature engineering
- Model selection and hyperparameter tuning
- Model evaluation and interpretation
- Making predictions on unseen data

## Dataset

The project utilizes a seismic dataset containing:
- Raw seismic signal measurements over time
- Event labels indicating the occurrence of an earthquake



## Features

- **Data Preprocessing:** Handling missing values, normalizing signals, feature extraction
- **Model Building:** Implementation of machine learning algorithms (e.g., Random Forests, CNNs, LSTMs)
- **Evaluation Metrics:** Accuracy, precision, recall, F1-score, confusion matrix
- **Visualization:** Plotting training history, feature distributions, and model performance
- **Predictions:** Using the trained model to predict future seismic events


## Results

After training and evaluating the model, the following results were obtained:

- **Training Accuracy:** ~95%
- **Validation Accuracy:** ~92%
- **Precision:** 91%
- **Recall:** 90%
- **F1-Score:** 90.5%

