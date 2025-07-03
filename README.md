# 🧠 Task 7: SVM Classifier – Breast Cancer Detection

🔗 **Dataset**: [Breast Cancer Wisconsin (Diagnostic) Dataset – Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)

---

## 📌 Objective
- Use Support Vector Machines (SVM) for binary classification
- Train using Linear and RBF kernels
- Apply hyperparameter tuning (C, gamma)
- Evaluate model using accuracy, precision, and recall

---

## 🧪 Steps
1. Load and clean `data.csv`
2. Drop unnecessary columns (like ID)
3. Convert labels: 'M' = 1, 'B' = 0
4. Handle missing values
5. Split and scale data
6. Train SVM (Linear and RBF)
7. Tune hyperparameters using GridSearchCV
8. Evaluate performance

---

## 📊 Results
| Model         | Accuracy |
|---------------|----------|
| Linear SVM    | ~96%     |
| RBF SVM       | ~98–99%  |

---

## 🛠️ Libraries Used
- `pandas`, `numpy`, `matplotlib`, `seaborn`
- `sklearn`: `SVC`, `StandardScaler`, `train_test_split`, `GridSearchCV`

---

## 💼 Interview Q&A

**1. What is a support vector?**  
👉 A data point near the margin that influences the hyperplane.

**2. What does the C parameter do?**  
👉 Controls trade-off between margin size and classification error.

**3. What are kernels in SVM?**  
👉 Functions that help SVM handle non-linear data (e.g., RBF, polynomial).

**4. Linear vs RBF kernel?**  
👉 Linear for linearly separable data; RBF for non-linear data.

**5. Advantages of SVM?**  
👉 Accurate, efficient in high dimensions, uses only support vectors.

**6. Can SVMs be used for regression?**  
👉 Yes, it’s called **SVR (Support Vector Regression)**.

**7. What happens when data is not linearly separable?**  
👉 Use non-linear kernels like **RBF** or **polynomial**.

**8. How is overfitting handled in SVM?**  
👉 Use proper C and gamma values, cross-validation, and regularization.

