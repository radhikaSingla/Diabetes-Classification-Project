# Diabetes Classification Project

## Overview

This project predicts whether a patient has diabetes using multiple machine learning classification algorithms. The objective was to compare different models and identify the best-performing predictive model.

---

## Dataset

The project uses the **PIMA Indians Diabetes Dataset**, which contains medical attributes such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

**Target Variable:**

- Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## Workflow

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Correlation Heatmap Visualization
- Outlier Detection using IQR
- Feature Scaling
- Train-Test Split
- Model Training and Evaluation

---

## Models Implemented

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- Gradient Boosting

---

## Results

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 82.09% |
| SVM | 82.09% |
| Random Forest | 77.61% |
| Gradient Boosting | 73.13% |

Logistic Regression and SVM achieved the highest accuracy of **82.09%**.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Structure

Diabetes-Classification-Project
│
├── classification.ipynb
├── README.md
└── dataset.csv 

---

## How to Run This Project

### Clone the repository

git clone https://github.com/radhikaSingla/Diabetes-Classification-Project.git

### Install required libraries

pip install pandas numpy matplotlib seaborn scikit-learn

### Open Jupyter Notebook

jupyter notebook

### Run classification.ipynb

---

## Conclusion

Among all tested models, Logistic Regression and SVM provided the best performance for diabetes prediction on this dataset.
