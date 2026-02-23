# Titanic Exploratory Data Analysis (EDA)

## Project Overview
This project conducts a comprehensive Exploratory Data Analysis on the Titanic dataset. The goal is to identify patterns, detect anomalies, and uncover the key factors that influenced passenger survival using Python and statistical visualization libraries.

## Dataset Description
* **Dataset:** Titanic Dataset (Ideal for mixed data type analysis).
* **Target Variable:** `Survived` (0 = No, 1 = Yes).
* **Key Features:** Age, Sex, Pclass (Class), Fare, Parch (Parents/Children), and SibSp (Siblings/Spouses).

## Analysis Workflow
1. **Data Inspection:** Loaded data and performed initial checks on shapes, data types, and null values.
2. **Data Cleaning:** - Handled missing values for 'Age' using the median.
   - Handled missing values for 'Embarked' using the mode.
3. **Statistical Analysis:** Generated summary statistics to observe central tendencies and spreads.
4. **Visual Exploration:**
   - **Distribution:** Analyzed Age and Fare distributions using histograms and boxplots.
   - **Categorical Analysis:** Evaluated survival rates by Gender and Passenger Class.
5. **Correlation & Relationships:**
   - Generated a Correlation Heatmap to see how variables like Fare relate to Survival.
   - Performed Cross-tabulation for survival percentages across different classes.
6. **Outlier Detection:** Used Z-Score analysis to identify extreme fares (>$500).
7. **Advanced Visualization:** Applied `FacetGrid` and `Pairplots` for multivariate pattern discovery.

## Key Conclusions
* **Socio-Economic Factor:** 63% of 1st-class passengers survived vs. 24% in 3rd class.
* **Gender & Age:** Women and children had significantly higher survival rates. 70% of children under 10 survived compared to 20% of men over 50.
* **The "Sweet Spot":** Survival peaked for women aged 20-40 in 1st and 2nd class.
* **Relationship Peak:** Data shows an inverse U-shaped relationship where survival peaks at age 28.
* **Fare Correlation:** A strong correlation exists between fare and survival (r=0.26).

## Recommendations
* **Feature Engineering:** Create a "Family Size" variable to see how traveling alone vs. in a group impacted survival.
* **Sub-group Study:** Investigate the factors behind the 38% mortality rate of women in 3rd class.

## Tech Stack
- **Python** (Pandas, NumPy)
- **Visualization** (Seaborn, Matplotlib)
- **Statistics** (SciPy)

---
*Project completed as part of Data Science Task 2.*