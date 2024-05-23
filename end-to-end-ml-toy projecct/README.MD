# End-to-End ML Toy Project: IQ, CGPA, and Placement Prediction

## Overview
This project demonstrates an end-to-end machine learning workflow using a toy dataset. The dataset consists of two independent features, IQ and CGPA, and one dependent feature, Placement. The goal is to build a classifier to predict Placement using Logistic Regression. The final model is serialized using `pickle` for future use.

## Dataset
- **Independent Features:**
  - `IQ`: Intelligence Quotient of the individual
  - `CGPA`: Cumulative Grade Point Average of the individual
- **Dependent Feature:**
  - `Placement`: Binary indicator of whether the individual was placed (1) or not (0)

## Steps
1. **Data Preparation:**
   - Load and preprocess the dataset, EDA and Feature Selection.
2. **Model Building:**
   - Train a Logistic Regression model using the independent features IQ and CGPA to predict Placement.
3. **Model Evaluation:**
   - Evaluate the model performance using appropriate metrics.
4. **Model Serialization:**
   - Serialize the trained model using `pickle` for future use.

## Requirements
- Python 3.x
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - pickle (standard library, no need to install separately)

## Installation
Install the required libraries using pip:


