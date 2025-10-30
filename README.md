# 💼 Salary Prediction in Ireland

## Overview
This project applies the **Data Analytics Lifecycle** to predict employee salaries in Ireland using real-world data.  
The goal is to identify key factors influencing salary levels (e.g., job title, industry, experience, education, and location) and build an accurate **regression model** for salary estimation.

---

## Business Problem
Accurately estimating salaries is valuable for:
- **Job seekers** to understand market pay expectations.
- **Employers** to benchmark compensation.
- **Recruitment platforms** to improve transparency and fairness.

The main task is to predict **annual salary (EUR)** based on available job-related and demographic features.

---

## Data
- **Source:** Scraped or collected from Irish job posting platforms (e.g., Jobs.ie) using Python web scraping tools.
- **Format:** CSV dataset containing job listings with fields such as:
  - `job_title`
  - `industry`
  - `location`
  - `experience_level`
  - `education`
  - `salary` *(target variable)*

The raw data is stored in the `data/` folder.

---

## Methodology
The analysis follows the **7-step Data Analytics Lifecycle**:

1. **Business Understanding** – Define salary prediction objectives.  
2. **Data Mining** – Collect Irish job market data via web scraping.  
3. **Data Cleaning** – Handle missing values, inconsistent formats, and outliers.  
4. **Exploratory Data Analysis (EDA)** – Examine distributions and correlations.  
5. **Feature Engineering** – Encode categorical variables, scale numerics, and create derived features (e.g., region grouping).  
6. **Predictive Modeling** – 
7. **Findings** – Summarize best model, key predictors, and limitations.

---

## Tools & Libraries
```txt
Python 3.10+
pandas
numpy
matplotlib
seaborn
scikit-learn
requests
beautifulsoup4
joblib
```

---

## Results
- **Best Model:** [example text]
- **Example Metrics:**  
  - [example text]
- **Top Predictors:**  
- [example text]

Visualizations and model outputs are included in the notebook.

---

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/theo-picar1/DSA_CA2_PairProject_SD3B.git
   cd DSA_CA2_PairProject_SD3B
   ```
2. Create a virtual environment and install dependencies:
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook notebooks/data_analysis.ipynb
   ```
4. The trained model and evaluation results will be saved in the `output/` folder.

---

## Folder Structure
```
├── data/                # Raw and cleaned data
├── notebooks/           # Jupyter notebooks
├── output/              # Saved models and charts
├── requirements.txt     # Dependencies
├── README.md            # This file
```

---

## Findings Summary
[example text]

---

## Authors
**Name:** Oisin Bell & Theo Picar
**Course:** Data Science 
**Date:** November 2025