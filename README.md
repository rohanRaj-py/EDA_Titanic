# 🚢 Titanic Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand the key factors influencing passenger survival.

The dataset used is a cleaned version of the Titanic dataset (commonly available in Seaborn), which includes engineered and simplified features.

---

## 🎯 Objective

To analyze the dataset and identify patterns affecting survival using statistical analysis and data visualization techniques.

---

## 📂 Dataset Description

The dataset contains the following features:

* **survived** – Survival status (0 = No, 1 = Yes)
* **pclass** – Passenger class (1, 2, 3)
* **sex** – Gender
* **age** – Age of passenger
* **sibsp** – Number of siblings/spouses aboard
* **parch** – Number of parents/children aboard
* **fare** – Ticket fare
* **embarked** – Port of embarkation
* **class** – Class category (First, Second, Third)
* **who** – Man, Woman, or Child
* **adult_male** – Whether passenger is an adult male
* **deck** – Deck information
* **embark_town** – Boarding location
* **alive** – Survival in text form (yes/no)
* **alone** – Whether passenger was alone

---

## ⚙️ Workflow

1. Data Loading
2. Data Inspection
3. Missing Value Analysis
4. Duplicate Check
5. Univariate Analysis
6. Bivariate Analysis
7. Feature Engineering
8. Correlation Analysis
9. Insights

---

## 🧹 Data Preprocessing

* Checked missing values in **age**, **deck**, and **embarked**
* Observed that **deck** has many missing values
* Verified dataset consistency and duplicates

---

## 📊 Exploratory Data Analysis

### 🔹 Univariate Analysis

* Distribution of **age** and **fare**
* Count of passengers based on **sex** and **class**

### 🔹 Bivariate Analysis

* Survival vs **sex**
* Survival vs **pclass**
* Survival vs **fare**

### 🔹 Correlation Analysis

* Heatmap used to analyze relationships between numerical features

---

## 🛠️ Feature Engineering

* Created **FamilySize** using sibsp and parch
* Categorized passengers into **family types**

---

## 🔍 Key Insights

* Female passengers had a much higher survival rate
* First-class passengers had better survival chances
* Higher fare is associated with higher survival probability
* Passengers traveling alone had different survival patterns

---

## 📈 Visualizations

* Count plots
* Histograms
* Heatmaps

---

---

## 🚀 Future Scope

* Handle missing values more effectively
* Add advanced feature engineering (Title extraction)
* Perform multivariate analysis
* Build machine learning models for prediction

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---



---

## 💡 Conclusion

The analysis shows that **gender, passenger class, fare, and travel conditions (alone/family)** significantly impact survival. These insights can be used for predictive modeling.

---
