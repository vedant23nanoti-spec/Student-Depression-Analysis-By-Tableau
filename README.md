# 🧠 Student Depression Analysis Dashboard (Tableau)

An interactive Tableau dashboard analyzing depression trends among students, exploring the impact of academic, lifestyle, and personal factors on mental health.

## 📌 Project Overview

This project analyzes a student mental health dataset to identify patterns and risk factors associated with depression — such as academic pressure, sleep duration, financial stress, and study satisfaction. The goal is to surface actionable insights that could help institutions identify at-risk student groups.

## 🎯 Objective

- Identify key factors correlated with student depression (academic pressure, sleep, CGPA, financial stress, etc.)
- Compare depression prevalence across gender, age group, and course/degree level
- Build an interactive dashboard for exploring risk patterns by segment

## 🗂️ Dataset
- **Fields used:** Age, Gender, Academic Pressure, CGPA, Sleep Duration, Financial Stress, Study Satisfaction, Depression (target)

## 🔧 Tools Used

- Tableau Public / Desktop
- Calculated fields for risk scoring/segmentation
- Filters and parameters for demographic drill-down

## 📊 Dashboard Components

| Sheet | Purpose |
|---|---|
| Overview KPIs | Total students analyzed, overall depression rate % |
| Demographic Breakdown | Depression rate by gender, age group |
| Academic Factors | Impact of academic pressure & CGPA on depression |
| Lifestyle Factors | Sleep duration & financial stress vs depression rate |
| Correlation View | Heatmap/scatter showing strongest contributing factors |

## 🧮 Key Calculated Fields

- Depression Rate % = `COUNT(Depression = Yes) / COUNT(Total Students)`
- Risk Segment = Categorization based on combined academic + lifestyle stress factors

## 📈 Key Insights

- [e.g., "Students with academic pressure rated 4+ show 2x higher depression rate"]
- [e.g., "Sleep duration under 5 hours correlates strongly with higher depression prevalence"]
- [e.g., "Financial stress is a stronger predictor than CGPA in this dataset"]

## 🚀 How to Explore

1. Open the live Tableau Public link above
2. Filter by Gender, Age Group, or Academic Pressure level
3. Hover over charts to view detailed breakdowns

## 🧠 What I Learned

- Handling sensitive survey-based data responsibly in visual analytics
- Building correlation-focused dashboards to highlight risk factors
- Translating raw survey data into actionable, human-centered insights

## ⚠️ Note

This analysis is for educational/portfolio purposes and is not a clinical or diagnostic tool. Findings are based on dataset patterns, not medical assessment.

## 📬 Contact

Connect with me on [LinkedIn](your-link-here) for feedback or collaboration.
