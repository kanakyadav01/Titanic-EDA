# Titanic Survival Prediction - Exploratory Data Analysis (EDA)

## 📌 Overview
This repository contains an Exploratory Data Analysis (EDA) of the Titanic dataset from the Kaggle competition.  
The goal is to understand the dataset, identify patterns in passenger survival, and prepare insights that could help in predictive modeling.

---

## 📂 Repository Contents
- **`Titanic_EDA.ipynb`** → Jupyter Notebook with complete EDA process, code, and visualizations.
- **`Concise_EDA_Report.pdf`** → A short PDF report summarizing the key findings.
- **`train.csv`** → Dataset used for analysis (if sharing is permitted).
  
---

## 🗂 Dataset Information
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic)
- **Rows:** 891 passengers  
- **Key Columns:** `Survived`, `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`
- **Missing Values:** `Cabin` (large), `Age` (some), `Embarked` (few)

---

## 🔍 Key Findings
1. **Survival Rate:** ~38% survived, 62% did not.
2. **Gender:** Female passengers had much higher survival rates than males.
3. **Class:** 1st class passengers survived more often than 2nd or 3rd.
4. **Age:** Younger passengers, especially children, had better survival chances.
5. **Embarked Port:** Passengers from port **C** had the highest survival rate.
6. **Fare:** Higher fares correlated with higher survival and better class.

---

## 🛠 Data Cleaning Steps
- Filled missing `Age` with median value.
- Filled missing `Embarked` with most common value (mode).
- Dropped `Cabin`, `PassengerId`, `Name`, and `Ticket` columns.

---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
