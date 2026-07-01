# 📊 Feature Selection and Dimensionality Reduction on MNIST Digits
A comprehensive machine learning project that evaluates and compares multiple feature selection and dimensionality reduction techniques on the MNIST Digits dataset. The project analyzes the trade-off between feature reduction, computational efficiency, and classification performance using various machine learning models.


## 🚀 Project Overview
High-dimensional datasets often contain redundant or irrelevant features that increase computational cost without significantly improving model performance. This project implements a complete feature engineering pipeline to compare feature selection and dimensionality reduction techniques for improving model efficiency while maintaining predictive accuracy.


## 🎯 Objectives
- Compare multiple feature selection techniques
- Apply Principal Component Analysis (PCA) for dimensionality reduction
- Evaluate classification performance before and after feature reduction
- Analyze the trade-off between model accuracy and computational efficiency
- Visualize model performance using informative plots


## 📂 Dataset
**Dataset:** Scikit-Learn Digits Dataset
- **Samples:** 1,797 handwritten digit images
- **Features:** 64 pixel intensity values
- **Classes:** 10 (Digits 0–9)


## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook


## ⚙️ Feature Engineering Techniques

### Feature Selection
- Variance Threshold
- SelectKBest
- Recursive Feature Elimination (RFE)

### Dimensionality Reduction
- Principal Component Analysis (PCA)


## 🤖 Machine Learning Models
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)


## 📈 Results

### Best Performance
| Metric | Value |
|---------|------:|
| Original Features | 64 |
| Reduced Features | 15 |
| Feature Reduction | **76.56%** |
| Classification Accuracy | **97.04%** |

### Key Highlights

- Achieved **97.04% classification accuracy** after dimensionality reduction.
- Reduced the feature space from **64 to 15 features**, decreasing memory usage by **76.56%**.
- Compared multiple feature selection strategies to identify the most effective approach.
- Demonstrated that dimensionality reduction can significantly improve computational efficiency while preserving predictive performance.

---

## 📊 Visualizations

The project includes:

- Accuracy Comparison
- Confusion Matrix
- PCA Visualization
- Feature Reduction Comparison
- Explained Variance Analysis


## git clone
https://github.com/your-username/ML_Feature_Reduction_Project.git
