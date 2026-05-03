# ❤️ Heart Disease Prediction - UCI Dataset Analysis

[![View Slides](https://img.shields.io/badge/View-Project_Slides-red?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white)](./UCI%20Heart%20Disease%20Data.pdf)
[![ML Practice](https://img.shields.io/badge/ML-Practice-blue?style=for-the-badge&logo=python&logoColor=white)](./UCI_heart_disease.ipynb)

## 📌 Overview
This project is a personal practice lab dedicated to exploring **Machine Learning (ML)** techniques. Using the world-renowned **UCI Heart Disease Dataset**, I implemented a complete data science pipeline—from Exploratory Data Analysis (EDA) to advanced model tuning—to predict the likelihood of heart disease in patients.

## 📽️ Project Summary & Presentation
For a high-level overview of my findings, analysis, and final results, you can click the button above or the link below:
- [📄 **Download/View Project Summary (PDF)**](./UCI%20Heart%20Disease%20Data.pdf)

---

## 📊 Dataset Information
The dataset consists of patient records with 14 key clinical attributes used for diagnosis:
- **Demographics**: Age, Sex.
- **Clinical Measurements**: Resting Blood Pressure (`trestbps`), Serum Cholesterol (`chol`), Fasting Blood Sugar (`fbs`), Maximum Heart Rate (`thalach`).
- **Clinical Symptoms**: Chest Pain Type (`cp`), Exercise-Induced Angina (`exang`).
- **ECG & Tests**: Resting ECG results (`restecg`), ST Depression (`oldpeak`), Slope of peak exercise ST segment, Number of major vessels, and Thalassemia.

## 🛠️ Tech Stack
- **Language**: Python 🐍
- **Environment**: Jupyter Notebook / Google Colab
- **Libraries**:
  - **Data Handling**: `Pandas`, `NumPy`
  - **Visualization**: `Matplotlib`, `Seaborn`
  - **Machine Learning**: `Scikit-learn`

## 🚀 Project Workflow
1.  **Exploratory Data Analysis (EDA)**: Understanding data distributions, identifying outliers, and analyzing feature correlations.
2.  **Data Preprocessing**: Handling categorical variables through encoding, feature scaling, and data splitting.
3.  **Model Implementation**:
    - **Logistic Regression**: A reliable baseline for binary classification.
    - **Support Vector Machine (SVM)**: Optimized for finding the best decision boundary.
    - **Random Forest**: An ensemble learning method to improve accuracy and prevent overfitting.
4.  **Hyperparameter Tuning**: Utilized `GridSearchCV` to find the optimal parameters for each model, focusing on the **F1-Weighted** metric.
5.  **Evaluation**: Models were evaluated based on **Accuracy**, **F1-Score**, and **ROC-AUC** curves.

## 💡 Learning Objectives
- Mastered data cleaning and feature engineering.
- Deepened understanding of supervised learning algorithms.
- Gained experience in model selection and hyperparameter optimization using cross-validation.

## 👤 Author
**Nguyen Dang Cole**
- GitHub: [@nguyendangcole](https://github.com/nguyendangcole)
- *Self-taught ML enthusiast on a journey to explore Data Science.*

---
*This project is part of my personal portfolio for learning and development.*
