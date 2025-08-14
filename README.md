# Customer_churn_prediction
Machine Learning project for predicting customer churn using data preprocessing, exploratory data analysis (EDA), and multiple classification models. Includes feature engineering, model evaluation, and insights to help reduce churn.
<br>
# Customer Churn Prediction

## Project Overview
This project predicts whether a customer is likely to leave (churn) based on various customer attributes and service usage patterns.  
By identifying high-risk customers early, businesses can take preventive actions to improve retention.

The workflow includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature encoding & scaling
- Model training & evaluation

---

## Dataset Information
**File:** `customer_churn.data.csv`

**Features include:**
- Customer demographics (e.g., gender, senior citizen, partner, dependents)
- Service details (e.g., phone service, internet service, contract type)
- Account information (e.g., tenure, monthly charges, total charges)
- Target variable: **Churn** (Yes/No)

---

## Steps Performed
1. **Data Loading** – Imported CSV dataset into pandas
2. **Data Cleaning** – Handled missing values, corrected data types
3. **EDA** – Visualized churn rates across different customer segments
4. **Encoding** – Converted categorical variables to numeric
5. **Feature Scaling** – Standardized numerical features
6. **Modeling**:
   - Logistic Regression
   - Decision Tree Classifier
   - Random Forest Classifier
   - Support Vector Machine (SVM)
7. **Model Evaluation** – Accuracy, Precision, Recall, F1-score, ROC-AUC

---

## Model Performance (Example)
| Model                    | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|--------------------------|----------|-----------|--------|----------|---------|
| Logistic Regression      | 0.80     | 0.72      | 0.67   | 0.69     | 0.83    |
| Decision Tree Classifier | 0.78     | 0.71      | 0.66   | 0.68     | 0.81    |
| Random Forest Classifier | 0.83     | 0.75      | 0.70   | 0.72     | 0.86    |
| SVM                      | 0.82     | 0.74      | 0.68   | 0.71     | 0.85    |

✅ **Random Forest Classifier** performed the best in this example.

---

