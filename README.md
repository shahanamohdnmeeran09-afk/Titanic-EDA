# 🚢 Titanic Dataset Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs an **Exploratory Data Analysis (EDA)** on the famous [Titanic dataset](https://www.kaggle.com/c/titanic).  
The objective is to identify patterns and insights that influenced passenger survival, focusing on **demographics, class, fare, and family size**.  

---

## 📊 Analysis Performed

### 1. Data Cleaning
- Handled missing values (imputed average age for missing `Age`).
- Checked for null values and unique values.
- Ensured correct data types for analysis.

### 2. Survival Analysis
- Count and percentage of survivors vs non-survivors.
- Visualization of overall survival distribution.

### 3. Sex-Based Analysis
- Passenger distribution by sex.
- Survival comparison between males and females.

### 4. Passenger Class Analysis
- Distribution of passengers across classes (`Pclass`).
- Survival breakdown by class and sex.

### 5. Age Analysis
- Age distribution histogram with KDE curve.
- Age distribution by sex.
- Age variation across passenger classes using boxplots.

### 6. Fare & Revenue Analysis
- Distribution of fares.
- Total and average revenue per class.
- Insights into ticket pricing and revenue contribution.


---

## 📈 Visualizations
The analysis uses **Seaborn** and **Matplotlib** for rich visualizations:
- Bar charts (survival counts, class distribution, sex survival rates).
- Histograms with KDE (Age, Fare).
- Boxplots (Age across classes).
- Grouped bar plots with `hue` (Class × Sex × Survival).
- FacetGrid plots (Age distribution by sex).

---

## 🛠️ Technologies Used
- **Python 3**
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `seaborn`

---

## 🔑 Key Insights
- **Survival Rate:** ~38% survived, ~62% did not.
- **Sex Factor:** Females had a much higher survival rate than males.
- **Class Factor:** 1st class passengers had the best survival chances; 3rd class had the worst.
- **Age Factor:** Children and young adults had better survival odds.
- **Fare:** Higher ticket fares correlated with better survival chances.


---

## 📂 Repository Structure


---

## 🚀 How to Run
1. Clone this repository:
   ```bash
 
---

## 🚀 How to Run
1. Clone this repository:
   ```bash
  
https://github.com/shahanamohdnmeeran09-afk/Titanic-EDA/
