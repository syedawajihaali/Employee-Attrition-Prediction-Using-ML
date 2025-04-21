# 💼 Employee Attrition Prediction

Welcome to the **Employee Attrition Prediction** project!  
This machine learning-based project identifies the key factors that contribute to employee turnover and predicts whether an employee is likely to leave the company.

---

## 💡 Project Objective

The goal of this project is to:

- Analyze employee data to understand the key drivers of attrition  
- Build predictive models to classify whether an employee will leave (`Attrition = Yes`) or stay (`Attrition = No`)  
- Use SHAP (SHapley Additive exPlanations) to interpret model predictions and highlight influential features

---

## 📂 Dataset

The dataset used in this project (`Employee.csv`) contains various employee-related features, including:

- `JobSatisfaction`  
- `WorkLifeBalance`  
- `YearsAtCompany`  
- `MonthlyIncome`  
- `OverTime`  
- `DistanceFromHome`  
- ... and many more

---

## 🧠 Machine Learning Models Used

- 🌲 **Random Forest Classifier**  
- ➕ **Logistic Regression**

These models were trained to predict employee attrition with high accuracy.

---

## 🧪 Workflow

1. **Data Loading & Exploration**  
   - Initial dataset inspection using `pandas` and visualizations with `seaborn`
  
2. **Data Preprocessing**  
   - Handled missing values  
   - Converted `Yes/No` to `1/0`  
   - Encoded categorical variables  
   - Applied feature scaling with `StandardScaler` (if needed)

3. **Model Building & Evaluation**  
   - Performed train-test split  
   - Trained **Random Forest** and **Logistic Regression**  
   - Evaluated models using classification reports

4. **Model Explainability using SHAP**  
   - Visualized feature importance using SHAP summary plots  
   - Interpreted how individual features influence predictions

---

## 📊 Visualizations

- Plots comparing `Attrition` with various features  
- SHAP summary plot showing the most influential features
- SHAP feature importance plot showing the most important features driving employee attrition

---

## 🔧 Technologies Used

- 🐍 Python  
- `pandas`, `numpy`  
- `matplotlib`, `seaborn`  
- `scikit-learn`  
- `SHAP`

---

## 📈 Results

- **Random Forest** outperformed Logistic Regression in both accuracy and precision  
- Top features influencing attrition included:
  - `OverTime`
  - `JobSatisfaction`
  - `Age`
  - `MonthlyIncome`
  - `Job Level`
  - `StockOption `

---

## 🧠 Insights
Certainly! Here's a slightly more detailed version while still keeping it concise:

---

## 🧠 Insights

Key factors driving attrition include **OverTime**, **low JobSatisfaction**, **low MonthlyIncome**, **younger age**, **lower JobLevel**, and **limited StockOptions**, all of which contribute to disengagement and higher turnover risk.  
To reduce attrition, companies should focus on promoting a healthier **work-life balance**, providing **fair and competitive pay**, and establishing **clear pathways for career growth and employee development**.

