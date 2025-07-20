# 🧠 Student Performance Prediction using Machine Learning

This project uses **Linear Regression** to predict students' final grades based on various academic, social, and demographic features. The dataset is taken from the UCI Machine Learning Repository and includes information about Portuguese and Mathematics students.

## 🎯 Objective

To build a regression model that accurately predicts a student’s final grade (`G3`) based on multiple factors like study time, past failures, parental education, internet access, and more.

---

## 📊 Dataset Overview

- **Source**: UCI Student Performance Dataset
- **Records**: 395 students
- **Features**: 32 (after preprocessing)
- **Target**: `G3` – Final exam grade (0 to 20)

---

## 🛠️ Preprocessing Steps

- ✅ Missing value handling
- ✅ Categorical encoding (One-hot + Label encoding)
- ✅ Outlier detection and removal (IQR, Z-score)
- ✅ Feature scaling (Standardization)
- ✅ Feature selection (Sequential Feature Selector)

---

## 📈 Model Used

- **Model**: Linear Regression
- **R² Score**: `0.9023` on test data

---

## 🔍 Feature Selection

Used **Sequential Feature Selector** from `sklearn` to select the most relevant features for the regression model, boosting both performance and efficiency.

---

## 📉 Error Analysis

- Plotted residuals to confirm a near-normal distribution
- Verified low bias and variance

---

## 💾 Future Improvements

- Try advanced regressors (e.g., XGBoost, RandomForestRegressor)
- Deploy the model via Flask or Streamlit
- Collect real-time student input via UI for predictions

---

## 📁 Files

- `student_performance_model.ipynb` – Main notebook
- `student-mat.csv` – Dataset used
- `student_grade_predictor.pkl` – Saved model
- `requirements.txt` – Required libraries

---

## 🙌 Acknowledgements

- UCI Machine Learning Repository
- Kaggle & StackOverflow Community

---

## 📢 Connect with Me

If you have feedback or suggestions, feel free to connect with me on [LinkedIn](https://www.linkedin.com/) or GitHub!


