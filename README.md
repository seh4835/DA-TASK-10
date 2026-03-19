# 📊 Customer Churn Prediction – End-to-End Preprocessing Pipeline

## 📌 Project Overview

Customer churn prediction is a critical problem in business analytics, where the goal is to identify customers who are likely to discontinue using a service.

This project focuses on building a **robust and reusable preprocessing pipeline** that prepares raw customer data for machine learning models.

The pipeline includes:
- Data cleaning
- Encoding categorical variables
- Feature scaling
- Outlier detection
- Feature engineering
- Feature selection
- Model integration

---

## 🎯 Objectives

- Understand customer behavior patterns
- Prepare high-quality input features for ML models
- Reduce noise and redundancy in data
- Improve model performance using engineered features
- Build a scalable preprocessing workflow

---

## 📂 Dataset Description

The dataset consists of **500 customer records** with the following attributes:

| Feature | Description |
|--------|------------|
| CustomerID | Unique identifier |
| Tenure | Number of months customer stayed |
| MonthlyCharges | Monthly bill amount |
| TotalCharges | Total amount charged |
| Contract | Contract type |
| PaymentMethod | Mode of payment |
| PaperlessBilling | Billing preference |
| SeniorCitizen | Whether customer is senior citizen |
| Churn | Target variable |

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🔄 Project Workflow

### 1. Data Exploration
- Dataset structure analysis
- Data type verification
- Churn distribution visualization

### 2. Data Preprocessing
- Missing value handling
- Removal of irrelevant columns
- Data type correction

### 3. Encoding Techniques
- Label Encoding (binary variables)
- One-Hot Encoding (nominal variables)
- Ordinal Encoding (ordered categories)

### 4. Feature Scaling
- Standard Scaling (mean = 0, variance = 1)
- Min-Max Scaling (range: 0 to 1)

### 5. Outlier Detection
- Interquartile Range (IQR)
- Z-score method

### 6. Feature Engineering
Creation of new features such as:
- Customer Lifetime Value
- Charges per tenure
- Contract-based scoring
- Payment efficiency
- Billing behavior score

### 7. Feature Selection
- Correlation analysis
- Feature importance using Random Forest

### 8. Pipeline Construction
- ColumnTransformer
- Pipeline API
- End-to-end automation

---

## 📈 Key Highlights

- ✔ Implemented **3 encoding methods**
- ✔ Applied **2 scaling techniques**
- ✔ Created **5+ engineered features**
- ✔ Performed **outlier handling using 2 methods**
- ✔ Built a **complete preprocessing pipeline**
- ✔ Generated **feature importance insights**

---

## 📊 Results

- Cleaned and structured dataset ready for modeling
- Improved feature quality through engineering
- Identified key features influencing churn
- Built reusable pipeline for future predictions

---

## 🚀 Future Improvements

- Add advanced models (XGBoost, LightGBM)
- Perform hyperparameter tuning
- Deploy model using Flask or FastAPI
- Integrate with real-time dashboards

---

## 👩‍💻 Author

Customer Churn Prediction Project  
Data Science / Machine Learning Pipeline Implementation
