# Atmospheric Pollution Analysis – Graz, Austria

**Case Study Project (2024)**  
As part of a university case study, we analyzed atmospheric pollution data in Graz, Austria, focusing on **NO₂** and **PM10** levels to understand the impact of human activity.

---

##  Project Objective
- Investigate which pollutant (NO₂ or PM10) is more influenced by human activity.  
- Test the impact of including/excluding human-activity predictors (e.g., day type).  
- Apply machine learning models to predict pollutant levels and evaluate performance.  

---

## Methods
- **Data Preprocessing & Feature Selection**  
  - Linear Regression diagnostics  
  - VIF (Variance Inflation Factor) check for multicollinearity  

- **Machine Learning Models**  
  - Random Forest Regressor (with GridSearchCV hyperparameter tuning)  
  - Linear Regression baseline models  

- **Evaluation Metrics**  
  - R² score (train/test sets)  
  - Feature importance analysis  

---

##  Key Findings
- **NO₂ predictions** achieved R² up to **0.82 (test set)**.  
- Human activity (“day type”) significantly improves NO₂ prediction accuracy.  
- PM10 showed weaker correlation with human activity → more dependent on natural factors.  
- Observed variance patterns changed after the first COVID-19 lockdown.  

---

##  Repository Contents
- `Case_Study_Presentation.pdf` → Final project slides with results and visualizations  
- `README.md` → Project documentation  

*(Note: Original Jupyter notebooks were on a school server and are not included. All methodology and results are summarized in the presentation.)*  

---

## 📈 Results Example
- Random Forest (NO₂): Train R² = 0.94, Test R² = 0.82  
- Random Forest (PM10): Train R² = 0.77, Test R² = 0.60  
