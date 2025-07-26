# 🍷 Wine Quality Prediction – Data Science Project

This project is a machine learning pipeline to predict the quality of red wines using physicochemical features. It is based on the popular UCI Wine Quality dataset and has been adapted and enhanced by **[Your Name]** to demonstrate end-to-end data science workflow including data analysis, modeling, and evaluation.

---

## 📌 Objectives

- Analyze physicochemical properties of red wine
- Identify patterns and trends using visualizations
- Apply machine learning models to classify wine quality
- Evaluate models using accuracy, precision, recall, F1-score
- Perform dimensionality reduction using PCA

---

## 🗂 Dataset

- 📍 **Source:** UCI Machine Learning Repository  
- 🔗 [Wine Quality Data (Red)](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)

**Attributes:**  
- Fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, alcohol  
- Target: Wine Quality (score 0–10)

---

## 🧠 Techniques Used

- Exploratory Data Analysis (EDA) using **Pandas, Matplotlib, Seaborn**
- Dimensionality reduction via **PCA**
- Classification Models:  
  - **Logistic Regression**  
  - **Random Forest**  
  - **XGBoost**
- Model performance metrics:  
  - Accuracy, Precision, Recall, Confusion Matrix, ROC AUC

---

## 🔍 Results

- Best model: **Random Forest**, ~78% F1 score  
- Top features: **Alcohol**, Volatile Acidity, Sulphates

---

## 🛠 Tools & Technologies

- Python, Jupyter Notebook  
- pandas, NumPy, scikit-learn, matplotlib, seaborn  
- XGBoost  
- (Optional) Flask / Streamlit for deployment  
- (Optional) MLflow for experiment tracking

---

## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/wine-quality-analysis.git
cd wine-quality-analysis
