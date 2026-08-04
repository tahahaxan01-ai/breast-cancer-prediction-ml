# Breast Cancer Prediction using Logistic Regression

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F79A3E?logo=scikit-learn&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

A machine learning pipeline designed to classify breast mass tumors as malignant or benign using Logistic Regression. Built with `scikit-learn`, this project demonstrates data cleaning, feature scaling, model evaluation, and structured code execution for medical diagnostic applications.

## Key Features

- **End-to-End ML Pipeline**: Covers exploratory data analysis (EDA), preprocessing, feature scaling, model training, and performance evaluation.
- **Data Leakage Prevention**: Applies feature scaling via `StandardScaler` to maintain strict boundaries between training and testing data splits.
- **Diagnostic Metrics**: Evaluates performance using Precision, Recall, F1-Score, and Confusion Matrix to minimize false negatives in medical diagnostics.

## Dataset Information

- **Features**: Continuous features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.
- **Target**: Diagnosis (`1 = Malignant`, `0 = Benign`).
- **File**: `breast_cancer_data.csv` (~120 KB) stored directly in the repository root.

## Technologies Used

- **Language**: Python
- **Data Manipulation**: Pandas, NumPy
- **Machine Learning**: Scikit-Learn
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook

## Quickstart & Setup

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/tahahaxan01-ai/breast-cancer-prediction-ml.git](https://github.com/tahahaxan01-ai/breast-cancer-prediction-ml.git)
   cd breast-cancer-prediction-ml
