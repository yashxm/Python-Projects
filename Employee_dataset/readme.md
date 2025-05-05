# Employee Data Analysis

This project explores an employee dataset to uncover trends related to demographics, job features, and attrition status using data analysis and a logistic regression model. The dataset was downloaded from kaggle- [Employee dataset](https://www.kaggle.com/datasets/tawfikelmetwally/employee-dataset/data)

## 📁 File

- `Employee_data.csv`: Raw csv file with employee data.
- `employee_data_analysis.ipynb`: Jupyter notebook containing data cleaning, EDA, and logistic regression implementation.

---

## 📊 Dataset Overview

The dataset includes:
- **Demographics**: Age, Gender, City
- **Job Features**: Payment Tier, Experience in Domain, Joining Year, EverBenched status
- **Target**: LeaveOrNot (employee attrition)

---

## 🧪 Analysis & Modeling Steps

### ✅ Data Cleaning
- Checked for null values and duplicates
- Removed duplicate entries

### 📌 Exploratory Data Analysis (EDA)
- Distribution analysis by features: City, Payment Tier, Gender, Experience, Age
- Attrition breakdown by each categorical feature
- Correlation heatmap

### 🤖 Logistic Regression Model

After preprocessing the data, a Logistic Regression model was trained to predict employee attrition (LeaveOrNot). The model was evaluated on accuracy and classification metrics.

**Model Highlights:**
- **Training/Test Split:** 80/20
- **Classifier Used:** Logistic Regression (`max_iter=1000`)
- **Accuracy:** ~0.65
- **Evaluation Metrics:** Precision, Recall, F1-score (reported for each class)

Full model implementation and evaluation details are available in the notebook.
