Titanic Dataset Analysis Report
📑 Introduction
The sinking of the Titanic was one of the deadliest maritime disasters in history. This analysis explores the factors influencing passenger survival, examining variables such as age, gender, class, and family connections. The aim is to identify patterns among survivors and provide insights into the factors that contributed to their survival.

🗂 Dataset Overview
This dataset includes key information on Titanic passengers, including demographics, travel details, and survival outcomes. Below are the fields used in this analysis:

age: Age of the passenger
age category: Categorized age groups (e.g., Child, Adult, Senior)
embarkfar: Fare paid by the passenger
barch: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
pclass: Passenger class (1 = First, 2 = Second, 3 = Third)
sex: Gender of the passenger
sibsp: Number of siblings/spouses aboard the Titanic
survivors: Whether the passenger survived (1 = Survived, 0 = Did not survive)

🔍 Data Cleaning & Transformation
Before conducting the analysis, the following steps were applied to ensure clean and consistent data:

Missing age values: Imputed with the median age for the respective class.
Categorized ages into groups:
baby: 0-3 years
kid: 3-12 years
young: 13-40 years
old: 40+ years
Embarkation data: 
S= Southampton
C = Cherbourg
Created survival labels for clarity: (1 = Survivor, 0 = Non-survivor).
Outliers in fare were capped at the 99th percentile.

📌 Conclusion
This analysis shows that survival on the Titanic was heavily influenced by gender, class, and age. Women, children, and first-class passengers had the best chances of survival. Additionally, traveling in smaller family groups and boarding from Cherbourg improved the odds of surviving the disaster.
