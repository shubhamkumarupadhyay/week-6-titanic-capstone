# Titanic Survival Prediction and Passenger Segmentation

## Week 6 – Integrative Capstone Project

This project is the final capstone project completed as part of my Data Science with Python internship.

The project uses the Titanic passenger dataset to demonstrate a complete data science workflow, including data preprocessing, exploratory data analysis, supervised machine learning, model evaluation, and unsupervised learning.

## Project Objectives

- Understand and preprocess the Titanic dataset
- Handle missing values and prepare the data
- Perform exploratory data analysis
- Create meaningful visualizations
- Predict passenger survival using machine learning
- Compare Logistic Regression and Random Forest
- Evaluate model performance
- Identify important predictive features
- Perform passenger segmentation using K-Means clustering
- Evaluate clustering using the Silhouette Score

## Dataset

The project uses the Titanic passenger dataset.

The dataset contains information such as:

- Passenger class
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Fare
- Cabin information
- Port of embarkation
- Survival status

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models

### Supervised Learning

Two classification algorithms were implemented:

1. Logistic Regression
2. Random Forest Classifier

The models were evaluated using test data, accuracy, classification reports, and a confusion matrix.

### Unsupervised Learning

K-Means clustering was used to identify passenger groups based on characteristics such as:

- Age
- Fare
- SibSp
- Parch
- Pclass

The Elbow Method and Silhouette Score were used to evaluate the clustering approach.

## Exploratory Data Analysis

The project includes visualizations for:

- Survival distribution
- Survival by gender
- Survival by passenger class
- Age distribution
- Fare distribution
- Correlation analysis

## Project Structure

```text
week-6-titanic-capstone/
│
├── README.md
├── Titanic-Dataset.csv
└── Week_6_Titanic_Capstone_Project.ipynb
