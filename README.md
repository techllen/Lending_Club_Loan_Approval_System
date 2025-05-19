# Lending_Club_Loan_Approval_System

This repository contains the code for a loan approval system using machine learning. It predicts loan default probability based on Lending Club data, including feature engineering, EDA, and model building with Logistic Regression, Random Forest, and XGBoost.

## Overview

This project develops a loan approval system to predict the probability of loan default using Lending Club data. It includes:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Feature engineering
* Model building and evaluation (Logistic Regression, Random Forest, XGBoost)
* Hyperparameter tuning and model selection

## Key Technologies

* Python
* Pandas, NumPy, Matplotlib, Seaborn
* Scikit-learn, XGBoost
* Imbalanced-learn (SMOTE)
* PyCaret (for comparison)

## Data

The dataset used is `loans.csv`, containing loan application information from Lending Club.

## Setup

1.  Clone the repository.
2.  Install the required Python packages (see the notebook for a detailed list).
3.  Ensure the dataset is available in the specified directory.
4.  Run the Python code to execute the analysis and model building.

## Usage

The code provides a step-by-step implementation of the loan approval system, from data loading and cleaning to model evaluation.

## Models

The following models were explored:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosting Classifier (XGBoost)

Each model's performance was evaluated using metrics like precision, recall, and F1-score. Hyperparameter tuning was performed to optimize model performance.

## Results

XGBoost generally performed best. For detailed results, refer to the notebook.

## Future Work

* Further hyperparameter tuning
* Exploring additional models
* Implementing more advanced feature engineering
* Developing a user interface for the system

## Credits

* Allen Matare Mwita (Author)

## License

This project is licensed under the MIT License.
