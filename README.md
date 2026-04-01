#Rock vs Mine Prediction using Machine Learning
Project Overview

This project is a supervised machine learning classification system that predicts whether an object detected by sonar signals is a rock or a mine.

The project uses two machine learning models:

Logistic Regression
Random Forest Classifier

Both models are trained and evaluated on the Sonar Dataset. Their performances are compared using accuracy scores to determine which model works better for this classification problem.

Problem Statement

Sonar systems are used to detect underwater objects. However, it is important to identify whether the detected object is a harmless rock or a dangerous mine.

This project automates the classification process using machine learning.

Dataset Information

The dataset used in this project is the Sonar Dataset.

Dataset Features
Total Features: 60
Feature Type: Numerical
Total Classes: 2
R = Rock
M = Mine

Each feature represents the energy of sonar signals reflected back from an object at different frequencies.

Technologies Used
Python
NumPy
Pandas
Scikit-learn
Logistic Regression
Random Forest Classifier
Jupyter Notebook
Machine Learning Workflow
Import required libraries
Load the sonar dataset
Perform preprocessing
Separate features and target variable
Split the data into training and testing sets
Train Logistic Regression model
Train Random Forest Classifier model
Compare both models using accuracy score
Predict whether the object is a rock or mine
Models Used
1. Logistic Regression

Logistic Regression is a supervised learning algorithm used for binary classification problems.

Advantages:

Simple and fast
Works well on small datasets
Good baseline model
2. Random Forest Classifier

Random Forest is an ensemble learning algorithm that combines multiple decision trees.

Advantages:

Can capture more complex patterns
Usually gives better performance on non-linear data
Reduces variance compared to a single decision tree
Model Comparison

The project compares both models based on:

Training Accuracy
Testing Accuracy
Overall Performance
