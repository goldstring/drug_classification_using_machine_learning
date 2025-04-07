# 🧪 Drug Classification using Machine Learning

This project aims to build a machine learning model that predicts the **type of drug** a patient should be prescribed based on demographic and clinical factors. The dataset contains features like age, sex, blood pressure, cholesterol level, and the sodium-to-potassium ratio in the blood.

---

## 📌 Problem Statement

Accurate drug prescription is essential in medical treatments. Given a patient’s data, can we classify the most appropriate drug? This is a **multiclass classification** problem where the target is to predict one of the several drug types.

---

## 📊 Dataset Description

| Feature | Description |
|---------|-------------|
| `Age` | Age of the patient |
| `Sex` | Gender of the patient (`Male` / `Female`) |
| `BP` | Blood Pressure Level (`LOW`, `NORMAL`, `HIGH`) |
| `Cholesterol` | Cholesterol Level (`NORMAL`, `HIGH`) |
| `Na_to_K` | Sodium to Potassium ratio |
| `Drug` | **Target**: Drug type prescribed (`DrugA`, `DrugB`, ..., etc.) |

---

## ⚙️ Technologies Used

- **Python**
- **Pandas**, **NumPy** – Data preprocessing
- **Matplotlib**, **Seaborn** – Data visualization
- **Scikit-learn** – Machine learning algorithms & evaluation
- (Optional) **Streamlit** – Deployment UI

---

## 🧰 Project Workflow

1. **Data Exploration & Cleaning**
2. **Encoding Categorical Variables**
3. **EDA: Correlation, Feature Distributions**
4. **Train-Test Split**
5. **Model Training & Evaluation**
   - Logistic Regression
   - K-Nearest Neighbors (KNN)
   - Decision Tree / Random Forest
   - Support Vector Machine (SVM)
6. **Model Comparison**
7. **Hyperparameter Tuning**
8. **(Optional) Model Deployment**

---

## 📈 Model Evaluation Metrics

- **Accuracy Score**
- **Confusion Matrix**
- **Classification Report (Precision, Recall, F1)**
- (Optional) **AUC-ROC Curve** for binary/multiclass classification

---

## ✅ Outcome

- Built a model to classify drug types with high accuracy.
- Identified important predictors influencing drug prescription.
- Demonstrated the ability to handle categorical and numerical data effectively.

---



