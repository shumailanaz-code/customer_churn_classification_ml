# 🔄 Customer Churn Prediction: Manual vs. Automated Feature Selection

## 📖 Project Overview

This project focused on building a robust machine learning pipeline to predict **customer churn** for a UK-based retail business using historical transaction data. 
The goal was to **compare the effectiveness of manual vs. automated feature selection** methods in improving classification model performance.

---

## 🎯 Objectives

- Engineer behavioral features from customer-level transaction data
- Compare **manual (domain + EDA)** vs. **automated (Genetic Algorithm)** feature selection
- Train and evaluate multiple classification algorithms
- Handle imbalanced data using **SMOTE**
- Assess model performance using key evaluation metrics

---

## 🧠 Feature Engineering

Features aggregated at the **customer level**:

- `Total_Quantity`
- `Total_Revenue`
- `Number_of_Invoices`
- `Recency`
- `Churn` (Target Variable)

---

## 🧪 Feature Selection Methods

1. **Manual Feature Selection**  
   - Based on domain knowledge and exploratory data analysis (EDA)
2. **Automated Feature Selection**  
   - Performed using a **Genetic Algorithm** to find the most predictive subset

---

## 🤖 Models Implemented

- **Logistic Regression**
- **Random Forest**
- **Gradient Boosting**
- **Support Vector Machine (SVM)**
- **Hybrid Ensemble Model**

Each model was evaluated on:
- **Imbalanced dataset**
- **SMOTE-balanced dataset**

---

## 📊 Evaluation Metrics

- **Accuracy**
- **Precision**
- **Recall**
- **F1 Score**
- **AUC-ROC**

Results were compared across both feature selection techniques and balancing methods.

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**, **NumPy** — Data wrangling
- **Scikit-learn**, **Imbalanced-learn** — Modeling & balancing
- **TPOT**, **DEAP** — Genetic Algorithm (AutoML)
- **Matplotlib**, **Seaborn** — Visualization
- **Jupyter Notebook**

---

## 🚀 How to Run

1. Clone the repository.
2. Place the dataset in the project directory.
3. Install required libraries:
   ```bash
   pip install pandas numpy scikit-learn imbalanced-learn deap tpot matplotlib seaborn
4. Run the notebook: (customer_churn_balance_classification_ml.ipynb & customer_churn_imbalance_classification_ml.ipynb)
5. Explore the model comparisons and final results.

---

## 📂 Data Source

- The dataset used for this project is the **Online Retail Dataset**, provided by the UCI Machine Learning Repository.
- It contains historical transactional data for a UK-based online retail store.
- Dataset link: [https://archive.ics.uci.edu/dataset/352/online+retail](https://archive.ics.uci.edu/dataset/352/online+retail)

