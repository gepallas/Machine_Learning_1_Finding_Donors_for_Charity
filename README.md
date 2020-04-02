# Supervised Learning to predict individuals' income to identify possible donors for charity
This project has been completed as part of the [Udacity's Machine Learning Nanodegree](https://www.udacity.com/course/intro-to-machine-learning-nanodegree--nd229) requirements.

The main file for the project is the *finding_donors.ipynb*.

A second file contains further personal experimentation of tuning various ML algorithms *finding_donors_Further_Experimentation.ipynb*.

## Overview
In this project I apply various supervised models to predict if the income of individuals is above or less than $50,000, using 1994 U.S. Census data. The best performing model is then selected for further tuning.

The jupyter notebook is structured as follows (more information at the finding_donors.ipynb file):
- Data Exploration
- Data Pre-processing
  - Logarithmic Transformation of skewed data (to reduce the high range of values caused by the outliers)
  - Normalization of numerical features (to ensure each feature is treated equally)
  - One-hot encoding of non-numeric features
  - Shuffle and split data into train and test sets
- Development of a Training and Predicting Pipeline for 4 different algorithms
  - Naive predictor
  - Logistic Regression
  - Support Vector Machines (SVMs)
  - AdaBoost
- Evaluation of model performance and selection of best performing model
  - Accuracy
  - F-beta score
- Model Tuning (of the model parameters to further improve its performance)
  - Grid Search Cross Validation
  - Re-evaluate the model performance
- Feature Importance (to identify few crucial features)
  - Re-evaluate the model performance to see how it performs when we only use a subset of all the available features

