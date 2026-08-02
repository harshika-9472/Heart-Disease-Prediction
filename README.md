# Heart Disease Prediction

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

## Project Overview

This project focuses on predicting the likelihood of heart disease in patients using supervised machine learning classification techniques. Cardiovascular diseases remain one of the leading causes of death worldwide, and early prediction can play a vital role in timely diagnosis and treatment.

The project follows a complete machine learning pipeline — starting from data loading and preprocessing, through exploratory data analysis, model training, and finally evaluating multiple classification algorithms to identify the best-performing model for heart disease prediction.

This project was developed as part of a B.Tech academic portfolio to demonstrate practical skills in data preprocessing, exploratory analysis, and applied machine learning.

## Features

- Import and load dataset
- Exploratory Data Analysis (EDA)
- Handle missing values
- Remove duplicate records
- Encode categorical variables
- Feature selection
- Train-test split
- Feature scaling
- Train multiple classification models
- Evaluate using Accuracy Score, Confusion Matrix, and Classification Report
- Compare model performance

## Technologies Used

- **Python** — Core programming language
- **Pandas** — Data manipulation and analysis
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical data visualization
- **Scikit-learn** — Machine learning model building and evaluation
- **Jupyter Notebook (VS Code)** — Development environment

## Dataset

The dataset used in this project contains patient health records with multiple clinical attributes such as age, blood pressure, cholesterol level, resting ECG results, and other relevant medical indicators that help determine the presence or absence of heart disease. Each record is labeled with a target variable indicating whether the patient has heart disease or not.

Before training the models, the dataset underwent thorough preprocessing including handling missing values, removing duplicate entries, and encoding categorical features to ensure clean and reliable input for the machine learning models.

## Machine Learning Models

The following classification algorithms were implemented and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

## Project Workflow

1. Import Libraries
2. Load Dataset
3. Perform EDA
4. Handle Missing Values
5. Remove Duplicates
6. Encode Categorical Variables
7. Select Features and Target
8. Split Dataset
9. Scale Features
10. Train Classification Models
11. Evaluate Models
12. Compare Model Performance

## Results

Each machine learning model was rigorously evaluated using **Accuracy Score**, **Confusion Matrix**, and **Classification Report** (which includes precision, recall, and F1-score) to provide a comprehensive assessment of predictive performance beyond raw accuracy alone.

The confusion matrix helped visualize the number of correctly and incorrectly classified cases for each class, while the classification report offered deeper insight into how well each model balanced precision and recall — an important consideration in medical prediction tasks where false negatives can be costly.

After comparing the performance of all trained models, the best-performing algorithm was identified based on its overall accuracy and balanced classification metrics, making it the most suitable choice for predicting heart disease on this dataset.

## Future Improvements

- Perform hyperparameter tuning (GridSearchCV / RandomizedSearchCV) to further optimize model performance
- Experiment with deep learning models (e.g., Artificial Neural Networks) for potentially higher accuracy
- Deploy the trained model as a web application using Flask or Streamlit for real-time accessibility
- Enable real-time prediction through a user-friendly interface where users can input clinical parameters
- Incorporate additional datasets to improve model generalization and robustness
- Apply advanced feature engineering and ensemble techniques to boost predictive performance

## Author

**Harshika**
B.Tech Student
