# Credit Card Fraud Detection 2023 Dataset Analysis & Machine Learning
### Author: Jonathan Wan 

This project uses the `Credit Card Fraud Detection Dataset 2023` which contains credit card transactions made by European cardholders in the year 2023. It comprises **over 550,000 records**, and the data has been anonymized to protect the cardholders' identities. The primary objective of this dataset is to facilitate the development of fraud detection algorithms and models to identify potentially fraudulent transactions.

## Key Features:
- `id` : Unique identifier for each transaction
- `V1-V28` : Anonymized features representing various transaction attributes (e.g., time, location, etc.)
- `Amount` : The transaction amount
- `Class` : Binary label indicating whether the transaction is fraudulent (1) or not (0)

*Data Source: The dataset was collected from credit card transactions made by European cardholders in 2023, with sensitive information removed to ensure privacy and compliance with ethical guidelines.*
https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023

## Goal: 
- Perform exploratory data analysis using data science techniques in Python/Jupyter Notebook and build machine-learning models for detecting credit-card frauds.

## Results:
- Initially, I experimented with a simple subset of features, `V1-V5`, for our classification model, resulting in a **6.6%** misclassification rate. While this provided a baseline, I sought to improve model performance further.

- I then explored more advanced techniques, including a **Bagging Classification model**, which achieved a significant reduction in the misclassification rate to just **0.06%** using all `V1-V28` features. This improvement demonstrated the value of ensemble methods in handling complex classification tasks.

- Subsequently, I employed a **Random Forest Classification model** with all `V1-V28` features, which further enhanced performance with a remarkable **0.01%** misclassification rate. The Random Forest's ability to capture complex relationships within the data was a key contributor to this achievement.

- The top 3 anonymized features that were most significant were `V1, V10, V14`.
