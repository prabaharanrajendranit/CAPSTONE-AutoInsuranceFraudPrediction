
# Auto Insurance Fraud Analytics

## Predicting Auto Insurance Fraud Using Crash Characteristics, Weather Conditions, and Socioeconomic Indicators

### Overview

This Data Analytics Capstone project investigates auto insurance fraud using crash characteristics, weather conditions, and socioeconomic indicators. The study integrates publicly available data from the National Highway Traffic Safety Administration (NHTSA), National Oceanic and Atmospheric Administration (NOAA), National Insurance Crime Bureau (NICB), U.S. Census Bureau, and Bureau of Labor Statistics (BLS) to develop predictive fraud detection models.

The primary objective is to identify factors associated with fraudulent claims and build machine learning models that can accurately classify insurance fraud risk.

---

## Research Questions

### RQ1
Which crash characteristics (e.g., crash severity, vehicle damage, driver behavior) significantly predict the likelihood of auto insurance fraud?

### RQ2
Do weather conditions (e.g., precipitation, visibility, temperature) moderate the relationship between crash characteristics and fraud likelihood?

### RQ3
Can machine learning models accurately classify fraudulent auto insurance claims using crash, weather, and socioeconomic variables?

### RQ4
Do socioeconomic factors influence geographic variation in insurance fraud prevalence?

---

## Objectives

- Identify crash-related predictors of insurance fraud.
- Evaluate weather-related influences on fraud risk.
- Assess socioeconomic drivers of fraud prevalence.
- Develop and compare machine learning classification models.
- Interpret model predictions using explainable AI techniques.
- Provide recommendations to improve fraud detection and claims investigation processes.

---

## Data Sources

- National Highway Traffic Safety Administration (NHTSA)
- National Oceanic and Atmospheric Administration (NOAA)
- National Insurance Crime Bureau (NICB)
- U.S. Census Bureau – American Community Survey (ACS)
- Bureau of Labor Statistics (BLS)

---

## Repository Structure

```text
Auto-Insurance-Fraud-Analytics
│
├── data/
│   ├── raw/
│   │   ├── nhtsa/
│   │   ├── noaa/
│   │   ├── nicb/
│   │   └── census/
│   │
│   └── processed/
│
├── notebooks/
│
├── src/
│
├── figures/
│
├── results/
│
├── appendix/
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Methodology

### Data Preparation
- Data acquisition and integration
- Data cleaning and preprocessing
- Missing value treatment
- Feature engineering
- Data transformation and normalization

### Statistical Analysis
- Descriptive statistics
- Correlation analysis
- Logistic regression
- Moderated regression analysis
