# ❤️ Heart Disease Prediction – Who's the Best Model?

This project focuses on building and comparing several machine learning models to accurately predict the presence of heart disease in patients. By leveraging real-world health data, the goal is to identify the most effective model for medical diagnosis support.

## 🧠 Overview

Heart disease is one of the leading causes of death globally. Early detection is critical to effective treatment and prevention. In this project, multiple machine learning classifiers are tested to determine which algorithm performs best in predicting heart disease based on a variety of health-related features.

> 🔍 Best Model Achieved **96% Accuracy**!

---

## 📊 Dataset

The dataset includes a mix of numerical and categorical features related to patients' health conditions. It contains 1,000 rows and multiple relevant features such as:

- `Age`
- `Gender`
- `Cholesterol`
- `Blood Pressure`
- `Heart Rate`
- `Smoking`
- `Alcohol Intake`
- `Exercise Hours`
- `Family History`
- `Diabetes`
- `Obesity`
- `Stress Level`
- `Blood Sugar`
- `Exercise Induced Angina`
- `Chest Pain Type`
- `Heart Disease` (Target)

The dataset is preprocessed to handle missing values, remove unimportant features, and encode categorical data.

---

## 🤖 Models Evaluated

The following machine learning models were trained and compared:

- Logistic Regression
- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting
- Gaussian Naive Bayes

Each model was evaluated using accuracy and classification metrics (precision, recall, F1-score), and results were visualized using confusion matrices.

---

## 🏆 Results

After evaluating all models, the **Support Vector Classifier (SVC)** achieved the best performance with **96% accuracy**, and it showed strong balance between precision and recall — making it suitable for real-world medical use.

---

## 📌 Technologies Used

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib & Seaborn
- Jupyter Notebook

