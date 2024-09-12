# Air-Quality

## Overview

The **Air Quality Prediction System** is a machine learning-based tool designed to predict the Air Quality Index (AQI) based on various pollutants such as Sulfur Dioxide (SO2), Nitrogen Dioxide (NO2), and Suspended Particulate Matter (SPM). The system calculates the AQI for a given set of pollutant data and classifies the air quality into different categories ranging from *Good* to *Hazardous*. This project aims to provide insights into air pollution levels and predict the AQI using multiple machine learning models.

## Features

- **Pollutant Index Calculation**: Calculate individual pollutant indexes for SO2, NO2, and SPM.
- **Air Quality Index (AQI) Calculation**: Compute the overall AQI based on the highest pollutant concentration.
- **AQI Classification**: Categorize AQI into various levels such as *Good*, *Moderate*, *Poor*, etc.
- **Machine Learning Models**: Train models like Linear Regression, KNN, and Decision Tree for AQI prediction.
- **Model Evaluation**: Evaluate models using accuracy and Kappa Score.
- **AQI Predictions**: Make AQI predictions for random input values.

## Dataset

The system uses air quality data containing pollutant values like SO2, NO2, RSPM (Respirable Suspended Particulate Matter), and SPM. The dataset is loaded into a pandas DataFrame for analysis and model training.
