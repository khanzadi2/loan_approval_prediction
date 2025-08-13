🧮 Loan Approval Prediction – Task 4
📌 Overview

This project builds a binary classification model to predict whether a loan application will be approved.
The solution includes data preprocessing, model training, and evaluation with a focus on precision, recall, and F1-score — metrics that are critical for imbalanced classification problems.

It also compares performance between Logistic Regression and Decision Tree models, both with and without SMOTE oversampling.

📂 Dataset

Recommended dataset: Loan Approval Prediction Dataset (Kaggle)

Target variable: Loan approval status (approved or not approved)

Features: Applicant income, credit history, loan amount, gender, marital status, etc.

⚙️ Features

Data loading from CSV, Google Drive, or Kaggle API

Data cleaning: handle missing values for numeric & categorical features

Feature engineering: one-hot encoding for categoricals, scaling for numerics

Class imbalance handling:

class_weight="balanced" for models

SMOTE (Synthetic Minority Oversampling Technique) for resampling

Model training & comparison: Logistic Regression vs Decision Tree

Evaluation metrics: Precision, Recall, F1-score, and Accuracy

🛠️ Tech Stack

Python 3

pandas, numpy – data manipulation

scikit-learn – preprocessing, models, evaluation

imbalanced-learn – SMOTE

matplotlib / seaborn – visualization

🚀 How to Run
1️⃣ Install dependencies
pip install pandas numpy scikit-learn imbalanced-learn matplotlib seaborn

2️⃣ Load the dataset

Update the CSV_PATH variable in the notebook with your dataset path.

3️⃣ Run the notebook

Execute all cells in Google Colab or Jupyter Notebook.

📊 Results (Example)
Model	SMOTE	Precision	Recall	F1-score
Logistic Regression	No	0.78	0.81	0.79
Decision Tree	No	0.75	0.79	0.77
Logistic Regression	Yes	0.81	0.83	0.82
Decision Tree	Yes	0.79	0.82	0.80

(These numbers are placeholders — replace with your actual results.)

📌 Author

Developed by Niba Shoukat as part of Task 4: Loan Approval Prediction.
