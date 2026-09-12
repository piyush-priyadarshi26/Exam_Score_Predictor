# Student Exam Score Predictor

An end-to-end Machine Learning project developed as part of the Python with Data Science Internship. This project implements a **Multiple Linear Regression** pipeline to analyze behavioral habits and predict a student's final academic performance index.

---

## 📌 Project Overview
Academic performance is influenced by daily lifestyle factors alongside past learning baselines. This model evaluates the joint impact of:
- **Daily Study Hours** ($X_1$)
- **Previous Exam Score** ($X_2$)
- **Average Sleep Duration** ($X_3$)

The objective is to train a predictive model that estimates the final **Performance Index (0–100%)** ($y$) on unseen test data.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Development Environment:** Jupyter Notebook
- **Data Manipulation:** `pandas`, `numpy`
- **Data Visualization:** `matplotlib`, `seaborn`
- **Machine Learning:** `scikit-learn` (`LinearRegression`, `train_test_split`, `r2_score`, `mean_squared_error`)

---

## 📂 Project Structure
```text
├── Student_Exam_Score_Predictor.ipynb  # Core Jupyter notebook with data pipeline and ML model
├── student_performance.csv             # Dataset containing 150 student profiles
└── README.md                           # Project documentation and summary
