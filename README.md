# titanic-survival-prediction
End-to-end Data Science Project using Titanic Dataset (EDA + ML Model)
# Titanic Survival Prediction

This project covers:
- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model

# 🚢 Titanic Survival Prediction (End-to-End Data Science Project)

## 📌 Overview

This project is an end-to-end data science workflow using the Titanic dataset. It includes data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation to predict passenger survival.

---

## 🎯 Objectives

* Perform data cleaning and preprocessing
* Conduct exploratory data analysis (EDA)
* Build a machine learning classification model
* Evaluate model performance using metrics

---

## 📊 Dataset Information

The dataset contains information about passengers aboard the Titanic.

### Key Features:

* **Pclass** → Passenger class
* **Sex** → Gender
* **Age** → Age of passenger
* **Fare** → Ticket fare
* **Embarked** → Port of embarkation

### Target Variable:

* **Survived** →

  * 0 = Did not survive
  * 1 = Survived

---

## 🛠️ Tools and Technologies Used

* Python 🐍
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔍 Steps Performed

### 1. Data Loading

* Loaded dataset using Pandas from an online source
* Displayed initial rows for understanding

---

### 2. Data Exploration

* Checked dataset shape, info, and summary statistics
* Identified missing values and data types

---

### 3. Data Cleaning

* Removed unnecessary columns (PassengerId, Name, Ticket, Cabin)
* Handled missing values:

  * Age → filled with mean
  * Embarked → filled with mode
* Converted categorical variables into numerical format

---

### 4. Exploratory Data Analysis (EDA)

* Visualized survival distribution
* Analyzed survival based on gender and class
* Observed age distribution
* Generated correlation heatmap

---

### 5. Feature Engineering

* Prepared features and target variable
* Converted categorical data using encoding

---

### 6. Model Building

* Used **Logistic Regression** for classification
* Split data into training and testing sets

---

### 7. Model Evaluation

* Evaluated using:

  * Accuracy
  * Precision
  * Recall
* Generated:

  * Confusion Matrix
  * Classification Report

---

## 📈 Key Insights

* Female passengers had a higher survival rate
* Passengers in higher classes had better chances of survival
* Age and fare also influenced survival probability

---

## 📊 Confusion Matrix Explanation

|                 | Predicted Positive  | Predicted Negative  |
| --------------- | ------------------- | ------------------- |
| Actual Positive | True Positive (TP)  | False Negative (FN) |
| Actual Negative | False Positive (FP) | True Negative (TN)  |

---

## 📁 Project Structure

titanic-survival-prediction/
│
├── titanic_analysis.ipynb
├── README.md
└── outputs/
└── confusion_matrix.png

---

## 🚀 How to Run the Project

1. Clone the repository:

```bash id="w28e7f"
git clone https://github.com/your-username/titanic-survival-prediction.git
```

2. Install required libraries:

```bash id="a7xk2q"
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook:

```bash id="y9dmq2"
jupyter notebook titanic_analysis.ipynb
```

---

## 📌 Results

* The model achieved good accuracy in predicting survival
* Precision and recall provided deeper insight into classification performance
* Confusion matrix helped visualize prediction results

---

## 📌 Conclusion

This project demonstrates a complete machine learning pipeline, from data preprocessing to model evaluation. It highlights how different features affect survival and emphasizes the importance of proper data analysis and evaluation techniques.

---

## 🔗 Author

**Kountik Das**

---

## ⭐ If you found this project useful, consider giving it a star!
