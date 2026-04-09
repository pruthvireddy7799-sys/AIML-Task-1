# 🚢 Titanic Data Preprocessing Project

## 📌 Overview

This project focuses on **data cleaning and preprocessing** of the Titanic dataset.
The goal is to transform raw data into a clean and structured format suitable for analysis and machine learning.

---

## 📂 Dataset

* Original Dataset: `Titanic.csv`
* Cleaned Dataset: `cleaned_titanic.csv`

---

## ⚙️ Steps Performed

### 1. Data Loading

* Loaded dataset using pandas

### 2. Handling Missing Values

* Filled missing `Age` values using mean
* Filled missing `Embarked` values using mode
* Dropped `Cabin` column (too many missing values)

### 3. Data Cleaning

* Removed unnecessary columns like `Name`, `Ticket`, `PassengerId`

### 4. Encoding Categorical Variables

* Converted `Sex` into numeric values
* Encoded `Embarked` column

### 5. Feature Scaling

* Standardized numerical columns like `Age` and `Fare`

---

## 🧰 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib / Seaborn (if used)

---

## 📊 Output

* Clean dataset ready for ML models
* Saved as `cleaned_titanic.csv`

---

## 🚀 How to Run

1. Install dependencies:

```
pip install -r requirements.txt
```

2. Open Jupyter Notebook:

```
jupyter notebook
```

3. Run:

```
notebook/data_preprocessing.ipynb
```

---

## 🎯 Learning Outcomes

* Data cleaning techniques
* Handling missing values
* Feature encoding
* Data preprocessing pipeline

---

## 📌 Author

Pruthvi
