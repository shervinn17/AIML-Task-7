# 🧠 Breast Cancer Classification using Support Vector Machines (SVM)

This project demonstrates how to use **Support Vector Machines (SVM)** for **binary classification** on a breast cancer dataset. Both linear and non-linear (RBF) kernels are used, along with visualizations, hyperparameter tuning, and model evaluation.

---

## 📌 Objective

- Use SVMs to classify tumors as benign or malignant.
- Visualize decision boundaries using PCA-reduced 2D data.
- Tune hyperparameters to improve performance.
- Evaluate model using cross-validation.

---

## 🛠️ Tools & Libraries

- **Python**
- **Scikit-learn**
- **NumPy**
- **Pandas**
- **Matplotlib**

---

## 📁 Dataset

- **File**: `breast-cancer.csv`
- **Target Column**: `diagnosis`
  - `M` → Malignant (1)
  - `B` → Benign (0)

---

## 🔧 Steps Performed

1. **Load and preprocess** the dataset (handle missing/irrelevant columns and encode labels).
2. **Standardize features** using `StandardScaler`.
3. **Dimensionality Reduction** with PCA (2D) for visualization.
4. **Train SVM models**:
   - Linear Kernel
   - RBF Kernel
5. **Visualize Decision Boundaries** for both models.
6. **Hyperparameter tuning** with `GridSearchCV` (optimize `C` and `gamma`).
7. **Model Evaluation**:
   - Classification reports
   - Cross-validation accuracy

---

## 📊 Results Summary

- **Best Model**: SVM with RBF kernel (after hyperparameter tuning)
- **Metrics Used**:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- **Visualization**: 2D PCA plots with decision boundaries

---

## 📈 Sample Outputs

- Decision boundary plots for both SVM models
- Classification report for each
- Best parameters from GridSearchCV
- Cross-validation accuracy scores

---

## 🚀 How to Run

1. Make sure required libraries are installed:
   ```bash
   pip install numpy pandas matplotlib scikit-learn
