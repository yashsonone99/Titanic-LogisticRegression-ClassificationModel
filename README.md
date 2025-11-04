# 🚢 Logistic Regression — Titanic Survival Prediction

This project demonstrates how to build a **Logistic Regression Classification Model** using the classic **Titanic dataset**.  
The goal is to predict whether a passenger survived or not based on attributes like age, sex, class, and fare.  

---

## 🎯 Objective
Predict **survival outcome (0 = Not Survived, 1 = Survived)** using passenger and travel features.

---

## 🧰 Tools & Libraries
- Python  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Joblib (for model saving)

---

## 🧩 Project Workflow

### 1️⃣ Data Loading
Loaded `Titanic_train.csv` and `Titanic_test.csv` datasets and combined them for consistent preprocessing.

### 2️⃣ Exploratory Data Analysis (EDA)
- Checked missing values and summary statistics  
- Visualized survival distribution by **Gender** and **Passenger Class**  
- Explored distributions of **Age** and **Fare**  

### 3️⃣ Data Preprocessing
- Imputed missing values using median/mode  
- Encoded categorical features (`Sex`, `Embarked`, `Pclass`)  
- Scaled numerical features using **StandardScaler**  

### 4️⃣ Feature Selection
Selected features for model input:
