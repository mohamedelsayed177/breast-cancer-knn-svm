# Breast Cancer Classification: EDA, Feature Selection, and Machine Learning

## 📌 Project Overview
This project focuses on building a **machine learning pipeline** for breast cancer classification using the **Breast Cancer Wisconsin dataset**.  
The workflow includes **data exploration, feature selection, model training, hyperparameter tuning, and evaluation**.

---

## 🔹 Objectives
1. Perform **Exploratory Data Analysis (EDA)** to understand the dataset.  
2. Apply **feature selection techniques** (ANOVA & Recursive Feature Elimination).  
3. Train **K-Nearest Neighbors (KNN)** and **Support Vector Machine (SVM)** models.  
4. Perform **hyperparameter tuning** using GridSearchCV.  
5. Compare model performance before and after tuning.  

---

## 🔹 Dataset
- **Source:** Scikit-learn’s built-in breast cancer dataset.  
- **Samples:** 569  
- **Features:** 30 numerical features → reduced to 25 after ANOVA → final 18 selected using RFE.  
- **Target Variable:**  
  - 0 = Malignant  
  - 1 = Benign  

---

## 🔹 Project Workflow
### 1. Data Exploration
- Checked data structure, summary statistics, and class distribution.  
- Verified **no missing or duplicated values**.  
- Visualized feature distributions and target balance.  

### 2. Feature Selection
- Removed features with high p-values (> 0.005) using **ANOVA F-test**.  
- Applied **Recursive Feature Elimination (RFE)** with linear SVM to select 18 best features.  

### 3. Model Training
- **Models Used:**  
  - K-Nearest Neighbors (KNN)  
  - Support Vector Machine (SVM)  

- **Default Hyperparameters Results:**  
  - KNN Accuracy: **95.6%**  
  - SVM Accuracy: **97.4%**  

### 4. Hyperparameter Tuning
- Applied **GridSearchCV** for both models.  
- **Best Results After Tuning:**  
  - KNN Accuracy: **96.5%**  
  - SVM Accuracy: **98.2%**  

### 5. Model Evaluation
- Evaluation Metrics: Accuracy, Precision, Recall, F1-score.  
- Confusion Matrix heatmaps for each model.  

---

## 🔹 Results & Conclusion
- Both models performed well, but **SVM consistently outperformed KNN**.  
- After tuning, SVM achieved **98.2% accuracy**, making it the best choice for this dataset.  

---

## 📊 Visualizations
- Distribution plots for numerical features.  
- Target variable distribution.  
- Confusion matrices for KNN & SVM.  

---

## 📂 Files
- `Breast Cancer Classification Using SVM And KNN.ipynb` → Full code implementation.  
- `README.md` → Project documentation.  

---

## 🔹 Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

##  Author
**Mohamed Elsayed**   
📧 [mohameddelsayed177@gmail.com](mailto:mohameddelsayed177@gmail.com)  


