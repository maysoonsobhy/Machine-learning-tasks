# 🤖 Machine Learning Tasks & Optimization Frameworks

Welcome to this repository! This project contains practical implementations of Machine Learning models, performance evaluation techniques, hyperparameter optimization frameworks, and theoretical guides on ensemble learning.

---

## 📌 Repository Contents

### 1. 📊 Naive Bayes Classifier (`Naive_Bayes.ipynb`)
- **Objective:** Implement a Gaussian Naive Bayes model to classify breast cancer tumors.
- **Dataset:** Scikit-learn Breast Cancer Wisconsin Dataset.
- **Key Workflow:**
  - Data loading, train-test splitting, and feature inspection.
  - Model training using `GaussianNB`.
  - Performance evaluation using Accuracy score, **Classification Report** (Precision, Recall, F1-score), and a **Confusion Matrix** heatmap.

---

### 2. 🎯 Hyperparameter Tuning with Optuna (`Optuna.ipynb`)
- **Objective:** Automate hyperparameter optimization for a Random Forest classifier using the **Optuna** framework.
- **Optimization Sampler:** Tree-structured Parzen Estimator (TPE).
- **Tuned Hyperparameters:**
  - `n_estimators` (Number of trees)
  - `max_depth` (Maximum depth of trees)
  - `min_samples_split`
  - `criterion` (`gini` vs `entropy`)
- **Visualizations (Plotly):**
  - Optimization History Plot
  - Hyperparameter Importances Plot
- **Results:** Achieved over **96% Test Accuracy** on unseen data.

---

### 3. 📚 Ensemble Learning Theoretical Report
- **Topics Covered:** Detailed breakdown and comparison between:
  - **Bagging** (Bootstrap Aggregating)
  - **Boosting** (Sequential error reduction)
  - **Stacking** (Meta-model blending)

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Core ML:** `scikit-learn`
- **Optimization:** `optuna`
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** `plotly`, `matplotlib`, `seaborn`
- **Environment:** Jupyter Notebook


