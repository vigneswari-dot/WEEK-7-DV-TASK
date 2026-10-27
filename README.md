# Week 7 – Student Performance Data Analysis

## 📌 Project Overview
This project focuses on analyzing student performance using Python and Pandas. It explores academic scores, checks data quality, and calculates statistical measures.

## 🎯 Objectives
- Load and explore the student performance dataset.
- Check missing values and duplicate records.
- Analyze math, reading, and writing scores.
- Calculate statistical measures.
- Calculate total scores and percentages.

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## 📂 Dataset
**Dataset Name:** StudentsPerformance.csv

The dataset includes:
- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch
- Test Preparation Course
- Math Score
- Reading Score
- Writing Score

## 🔍 Data Exploration
The following functions are used:

- `df.head()` – Displays the first 5 rows.
- `df.tail()` – Displays the last 5 rows.
- `df.describe()` – Shows statistical summaries.
- `df.shape` – Displays rows and columns.
- `df.columns` – Displays column names.
- `df.info()` – Shows dataset information.
- `df.isnull().sum()` – Checks missing values.
- `df.duplicated().sum()` – Counts duplicate records.

## 📊 Statistical Analysis
The project calculates:

- Mean
- Median
- Mode
- Standard Deviation
- 25th Percentile
- 50th Percentile
- 75th Percentile

## 🧮 Score Calculation

**Total Score:**

Total Score = Math Score + Reading Score + Writing Score

**Percentage:**

Percentage = (Total Score / 300) × 100

## ✅ Conclusion
This project provides a basic understanding of student academic performance through data exploration and statistical analysis. It helps analyze student scores and calculate total marks and percentages using Python.
