# crop-prediction-ml# Crop Yield Prediction using Machine Learning

## Overview
This project implements a machine learning model to predict crop yield using real-world agricultural and climatic data.  
The goal is to demonstrate a complete ML pipeline including data preprocessing, feature engineering, model training, evaluation, and result interpretation.

## Dataset
The dataset contains agricultural data with the following key attributes:
- Crop type  
- Region (Area)  
- Year  
- Average rainfall per year (mm)  
- Pesticide usage (tonnes)  
- Average temperature (°C)  
- Crop yield (hg/ha)

The dataset is included in this repository under the `data/` directory.

## Problem Statement
Build a predictive model that estimates crop yield based on climatic and agricultural factors.

## Approach
1. Loaded and cleaned the dataset  
2. Removed missing and irrelevant values  
3. Encoded categorical features such as crop type and region  
4. Selected relevant numerical and encoded features  
5. Split data into training and testing sets  
6. Trained a Linear Regression model  
7. Evaluated the model using MAE, MSE, and R² score  
8. Visualized actual vs predicted crop yield  

## Features Used
- Year  
- Average rainfall per year  
- Pesticide usage  
- Average temperature  
- Encoded crop type  
- Encoded region  

## Model Used
- Linear Regression (scikit-learn)

The model was selected for its simplicity and interpretability as a baseline regression approach.

## Results
The model successfully predicts crop yield trends based on available features.  
Performance metrics indicate reasonable prediction capability given the dataset size and feature diversity.

## Model Performance Visualization
![Actual vs Predicted Crop Yield](actual_vs_predicted.png)

*Figure: Comparison between actual and predicted crop yield values.*

## Prediction Example
The trained model is used to predict crop yield for a future year (2026) using example climatic and agricultural inputs.

## Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- Matplotlib  
- Google Colab  

## How to Run
1. Open the notebook `crop_yield_prediction.ipynb`  
2. Run all cells sequentially  
3. The dataset is automatically loaded from the `data/` folder  

## Conclusion
This project demonstrates a structured machine learning workflow applied to real-world agricultural data.  
It emphasizes correct data handling, model evaluation, and interpretability rather than solely focusing on accuracy.
