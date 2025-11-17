# AI-MINI-PROJECT

The dataset contains:
- 150 samples  
- 4 numeric features  
- 3 Iris species (Setosa, Versicolor, Virginica)

---

##  Project Objective

- Preprocess and explore the Iris dataset  
- Train multiple machine learning models  
- Compare their accuracies on unseen test data  
- Identify the best-performing algorithm  
- Visualize model performance using a bar chart  

This project demonstrates how different ML models behave on the same dataset.

---

##  Machine Learning Models Used

The following models were implemented:

1. **Logistic Regression**  
2. **K-Nearest Neighbors (KNN)**  
3. **Support Vector Machine (SVM – Linear Kernel)**  
4. **Decision Tree Classifier**

All models were trained on **scaled** data using StandardScaler.

---

##  Technologies & Libraries

- Python 3  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  

---

##  Results Summary

| Model | Accuracy (%) |
|-------|--------------|
| Logistic Regression | ~96–97% |
| K-Nearest Neighbors | ~95–97% |
| Decision Tree | ~92–95% |
| **SVM (Linear Kernel)** | **~97–98% (Best)** |

###  Best-performing model: **SVM (Linear Kernel)**  
It achieved the highest accuracy and produced the most stable predictions.

---

##  How to Run the Project

### 1. Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib
