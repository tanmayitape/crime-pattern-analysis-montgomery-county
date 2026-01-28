# Crime Pattern Analysis – Montgomery County (2018–2022)

## Executive Summary
This project analyses large-scale police incident data from Montgomery County, USA, covering the period **2018 to 2022**. The objective is to uncover meaningful **temporal, spatial, and categorical crime patterns** using structured exploratory data analysis and visual analytics.

The work focuses on transforming a complex, incomplete real-world dataset into **clear, reliable, and decision-ready insights**, with strong emphasis on data quality, methodological discipline, and interpretability.

---

## Why This Project Matters
Public safety data is often messy, incomplete, and easy to misinterpret if analysed carelessly.  
This project demonstrates how disciplined analytics can be used to:

- Identify high-risk periods and locations
- Understand which crime types dominate overall volume
- Support informed decisions around policing, prevention, and resource allocation

Rather than predictive modelling, this study prioritises **trustworthy descriptive and diagnostic analytics**, ensuring conclusions are grounded and explainable.

---

## Key Analytical Questions
The analysis is driven by clearly defined questions, including:

1. How do crime incidents vary year by year across major crime categories?
2. Which offence types contribute most to overall crime volume?
3. How does crime differ between residential and commercial areas?
4. Which streets and police districts report the highest victim counts?
5. Are there consistent seasonal or monthly crime patterns?
6. At what times of day do crime incidents peak?
7. How do victim counts vary across police beats over time?
8. Which offences dominate during peak crime hours?

Each question is addressed using targeted visual and statistical analysis.

---

## Dataset Overview
- **Source:** Public crime dataset (Data.gov / Kaggle mirror)
- **Records:** 300,000+ incident-level entries
- **Time coverage:** 2016–2022 (filtered to 2018–2022)
- **Features:** Crime type hierarchy, timestamps, location data, victims, police districts

---

## Data Preparation & Quality Control
Significant effort was invested in ensuring data reliability before analysis.

Key steps included:
- Handling **49,000+ missing timestamps** using logical imputation
- Filtering the dataset to the relevant analysis period
- Removing fields with excessive missing values and low analytical value
- Standardising categorical variables and handling undefined values explicitly
- Engineering time-based features such as year, month, hour, and day of week
- Verifying absence of duplicate records after cleaning

The final dataset contains **no missing values** in core analytical fields.

---

## Methodology
The analysis follows a structured workflow:

1. Initial data assessment and missing-value analysis  
2. Data cleaning and feature engineering  
3. Exploratory Data Analysis (EDA)  
4. Cross-sectional and temporal comparisons  
5. Insight synthesis aligned to the original questions  

Visualisations were deliberately chosen based on analytical purpose, including bar charts, line charts, boxplots, and heatmaps.

---

## Key Insights
Some of the most important findings include:

- **Crime concentration:**  
  The top 10 offence types account for approximately **51% of all reported incidents**, indicating strong concentration.

- **Residential exposure:**  
  Residential areas experience higher crime volumes than commercial zones, particularly for property-related offences.

- **Time-of-day peak:**  
  Crime incidents consistently peak around **3:00 PM**, a valuable signal for operational planning.

- **Seasonality:**  
  Summer months, especially **July**, show elevated crime and victim counts across multiple categories.

- **Geographic imbalance:**  
  A small number of police districts and streets account for a disproportionate share of incidents and victims, with **Silver Spring** reporting the highest overall volume.

- **Post-2020 decline:**  
  Overall crime levels decline after 2020, potentially reflecting behavioural changes following the COVID period.

---

## Tools & Techniques
- **Python:** Pandas, NumPy  
- **Visualisation:** Matplotlib, Seaborn  
- **Analytics:** Exploratory Data Analysis, feature engineering, descriptive statistics  
- **Practices:** Data validation, reproducible analysis, structured documentation  

---

## Repository Structure
