# 🔥 Calories Burnt Prediction Using Machine Learning

## 📘 Project Overview
This project aims to develop a **machine learning-based system** to accurately predict the number of calories burnt during various physical activities.  
Fitness monitoring is essential for maintaining a healthy lifestyle, and accurate calorie estimation can help individuals track and achieve their fitness goals.

Traditional methods like wearables and BMR-based formulas often lack accuracy and personalization.  
This project leverages **data-driven machine learning models** trained on a real-world dataset to improve calorie prediction performance.

---

## 📊 Dataset
The dataset used is **`calories.csv`**, which contains the following features:

| Feature | Description |
|----------|--------------|
| `Gender` | Male / Female |
| `Age` | Age of the individual (years) |
| `Height` | Height in centimeters |
| `Weight` | Weight in kilograms |
| `Duration` | Duration of activity (minutes) |
| `Heart_Rate` | Average heart rate during the activity |
| `Body_Temp` | Average body temperature during the activity |
| `Calories` | Target variable — calories burnt |

---

## ⚙️ Models Implemented
The following regression algorithms were implemented and evaluated:

1. **Linear Regression**  
2. **K-Nearest Neighbors Regressor (KNN)**  
3. **Support Vector Regressor (SVR)**  
4. **Random Forest Regressor**  
5. **XGBoost Regressor**

Each model was trained and evaluated based on **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **R² Score**.

---

## 🧠 Workflow
1. **Data Preprocessing**
   - Handle missing values
   - Encode categorical features (Gender)
   - Normalize / scale numerical features  
2. **Exploratory Data Analysis (EDA)**
   - Visualize correlations and distributions
   - Detect outliers and trends  
3. **Model Training & Evaluation**
   - Split dataset into training and testing sets
   - Train each model and compare performance  
4. **Model Deployment (optional)**
   - Save best model using `joblib` or `pickle`
   - Provide prediction interface for new inputs  


---

## 🧩 Technologies Used
- Python 3.x  
- NumPy, Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  

---

