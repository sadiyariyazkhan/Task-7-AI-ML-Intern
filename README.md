# Task-7-AI-ML-Intern
# Support Vector Machines (SVM) - Linear & Non-linear Classification

## Objective
Use **Support Vector Machines (SVMs)** for both **linear and non-linear classification** tasks.

## Tools & Libraries
- Python
- Scikit-learn  
- NumPy  
- Matplotlib  

---

## Steps Performed

1**Load & Prepare Dataset**  
- Used the **Breast Cancer Dataset** from `sklearn.datasets`.  
- Scaled features using `StandardScaler` for better SVM performance.  

2**Train SVM Models**  
- Implemented two classifiers:
  - Linear Kernel (`kernel='linear'`)
  - RBF Kernel (`kernel='rbf'`)

3**Model Evaluation**  
- Evaluated using **Accuracy**, **Confusion Matrix**, and **Classification Report**.  
- Compared linear vs RBF kernel results.  

4**Decision Boundary Visualization**  
- Plotted 2D decision regions for both kernels using only first two features.  

5**Hyperparameter Tuning**  
- Used `GridSearchCV` to find best values for **C**, **gamma**, and **kernel**.  

6**Cross-Validation**  
- Applied 5-fold cross-validation to evaluate model robustness.  

---

## 📊 Results Snapshot
| Model Type | Accuracy |
|-------------|-----------|
| Linear SVM  | ~96% |
| RBF SVM     | ~98% |

*(Values may vary slightly due to data splits.)*

---

## 📈 Visualizations
- Decision Boundary for Linear Kernel  
- Decision Boundary for RBF Kernel  
---
##  Author
**Sadiya Riyaz Khan**  
*AI/ML Enthusiast | Python Developer | Data Science Learner*  
GitHub: [sadiyariyazkhan](https://github.com/sadiyariyazkhan)

---
# Run the script
python SVM_Classification.py
