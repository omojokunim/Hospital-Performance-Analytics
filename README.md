
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Healthcare-Analytics-red) 

---

#  Project Overview

Healthcare organizations generate large volumes of clinical and operational data every day. Extracting meaningful insights from these datasets is essential for improving patient outcomes, reducing operational costs, and supporting evidence-based decision-making.

This project analyzes hospital performance data from **Lagos University Teaching Hospital (LUTH)** using Python. The analysis combines descriptive analytics, operational KPIs, statistical analysis, visualization, and machine learning to evaluate hospital performance across multiple dimensions.

The notebook demonstrates a healthcare analytics workflow including:

* Data cleaning
* Feature engineering
* KPI development
* Department performance analysis
* Physician performance evaluation
* Operational efficiency analysis
* High-risk patient identification
* Time series analysis
* Predictive modeling
* Executive-ready visualizations

---

#  Project Objectives

The analysis aims to:

* Evaluate overall hospital performance
* Measure key operational KPIs
* Analyze patient outcomes
* Assess departmental performance
* Compare physician performance
* Identify high-risk patient groups
* Evaluate healthcare costs
* Analyze patient satisfaction
* Monitor mortality trends
* Build predictive models for healthcare decision support

---

#  Dataset

The dataset contains hospital-level clinical and operational information including:

* Patient demographics
* Department
* Treating physician
* Admission and discharge dates
* Length of stay
* Treatment type
* Hospital outcome
* Cost of care
* Follow-up requirement
* Patient satisfaction score

Additional features were engineered during preprocessing:

* Cost per day
* Mortality indicator
* Age group
* Monthly admission period
* High-cost patient flag
* Long-stay patient flag

---

# 🛠 Tools & Technologies

| Tool             | Purpose                      |
| ---------------- | ---------------------------- |
| Python           | Data Analysis                |
| Pandas           | Data Cleaning & Manipulation |
| NumPy            | Numerical Computing          |
| Matplotlib       | Data Visualization           |
| Seaborn          | Statistical Visualization    |
| Scikit-learn     | Machine Learning             |
| Jupyter Notebook | Development Environment      |

---

#  Project Workflow

## 1. Data Loading

* Imported hospital dataset
* Verified structure
* Checked dimensions
* Reviewed data types

---

### 2. Data Cleaning & Feature Engineering

Performed:

- Date conversion
- Missing value handling

**Feature Engineering**

- Age grouping
- Cost per day calculation
- Mortality flag creation
- Long-stay identification
- High-cost patient identification
---

## 3. Exploratory Data Analysis (EDA)

Explored:

* Patient demographics
* Outcome distribution
* Hospital costs
* Length of stay
* Satisfaction distribution
* Department statistics

---

#  Key Performance Indicators (KPIs)

The notebook computes the following hospital performance metrics including:

* Total Patients
* Average Length of Stay (ALOS)
* Average Cost per Patient
* Average Cost per Day
* Average Patient Satisfaction
* Mortality Rate
* Follow-up Requirement Rate

---

#  Department Performance Analysis

Each hospital department was evaluated using:

* Patient volume
* Average length of stay
* Average treatment cost
* Cost per day
* Mortality rate
* Average satisfaction score

This helps identify:

* High-performing departments
* Cost-intensive departments
* Departments requiring operational improvement

---

#  Doctor Performance Analysis

Performance comparisons were carried out across physicians to evaluate:

* Patient volume
* Average treatment cost
* Patient satisfaction
* Clinical outcomes

This analysis can support:

* Workforce planning
* Performance evaluation
* Quality improvement initiatives

---

#  Operational Efficiency Analysis

Operational metrics include:

* Average Length of Stay
* Median Length of Stay
* Monthly Patient Throughput
* Approximate Bed Turnover Rate

These indicators provide insights into hospital resource utilization and patient flow.

---

#  Time Series Analysis

Monthly trends were analyzed for:

* Patient admissions
* Mortality rate
* Average hospital cost
* Average length of stay

Trend analysis supports healthcare planning and seasonal demand forecasting.

---

# ⚠ High-Risk Patient Segmentation

Patients were categorized as high-risk using indicators such as:

* Mortality
* Long hospital stay
* High treatment cost

---

#  Visualizations

The notebook contains multiple visualizations including:

* Correlation Heatmap
* Mortality by Age Group
* Department Comparisons
* Cost Distribution
* Monthly Admission Trends
* KPI Charts
* Operational Performance Charts

---

#  Machine Learning

The project includes predictive healthcare analytics using **Random Forest Regression**.

## Model 1

### Predict Length of Stay

Features include:

* Age
* Department
* Gender
* Treatment
* Mortality
* Cost
* Satisfaction

Performance metrics:

* Mean Absolute Error (MAE)
* R² Score
* Feature Importance

---

## Model 2

### Predict Hospital Efficiency Score

A composite efficiency score was developed using:

* Length of stay
* Patient survival
* Satisfaction score

Random Forest Regression was used to predict operational efficiency.

---

#  Business Insights

The analysis helps hospital management:

* Improve operational efficiency
* Reduce unnecessary hospital stays
* Identify high-cost treatment patterns
* Monitor mortality trends
* Improve patient satisfaction
* Allocate resources effectively
* Improve departmental performance
* Support evidence-based decision-making

---

#  Sample Outputs

Consider adding screenshots of:

* Correlation Heatmap
* KPI Dashboard
* Department Performance Table
* Monthly Trends
* Feature Importance Plot

Store images inside:

```text
images/
```

Example:

```markdown
![Dashboard](images/dashboard.png)
```

# 📈 Future Improvements

Potential enhancements include:

* Interactive Power BI dashboard
* SQL database integration
* Hospital occupancy forecasting
* Readmission prediction
* Mortality classification model

---

# 👨‍💻 Author

**Michael Omojokun**

Healthcare Data Analyst | Dentist | MPH Candidate


Email: omojokunim@gmail.com

LinkedIn - https://www.linkedin.com/in/iyanuoluwaomojokun
