---
title: "Titanic Passenger Data Analysis"
excerpt: "Python-based exploratory data analysis of the Titanic passenger dataset with modular code, visualizations, and bilingual notebook reports."
last_modified_at: 2026-05-26
categories:
  - projects
tags:
  - Python
  - Data Analysis
  - Pandas
  - Data Visualization
  - Exploratory Data Analysis
permalink: /projects/titanic-passenger-data-analysis/
---

<div style="font-size: 0.8em;" markdown="1">

# Titanic Passenger Data Analysis

---

A modular Python project exploring the Titanic dataset through data cleaning, exploratory data analysis, and visualization.

This project investigates how different factors such as gender, age group, embarkation port, and passenger class influenced survival rates during the Titanic disaster.

---

# Project Structure

```text
Titanic/
├── data/
│   └── Titanic.csv
│
├── outputs/
│   ├── survival_by_cabin.png
│   ├── survival_by_gender.png
│   └── survival_by_port.png
│
├── data_loader.py
├── gender.py
├── children.py
├── port.py
├── cabin.py
├── main.py
│
├── REPORT_EN.ipynb
├── REPORT_FR.ipynb
└── running.ipynb
```

---

# Features

- Modular Python project structure
- Data loading and preprocessing
- Survival analysis by:
  - Gender
  - Age group
  - Embarkation port
  - Passenger class
- Automatic chart generation with Matplotlib
- Separation between analysis logic and execution workflow

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

# Example Analyses

The project compares male and female survival rates and visualizes the results using pie charts.

## Survival Rate by Gender

The analysis investigates the survival probability across different genders

<div>

<img src="/assets/outputs_titanic/survival_by_gender.png" />

</div>

## Survival Rate by Passenger Class

The analysis investigates how ticket class influenced survival probability.

<div>

<img src="/assets/outputs_titanic/survival_by_cabin.png" />

</div>

## Survival Rate by Embarkation Port

Passenger survival is compared across embarkation locations (`C`, `Q`, `S`).

<div>

<img src="/assets/outputs_titanic/survival_by_port.png" />

</div>

---

# Purpose of the Project

This project was created as a practice exercise in:

- Exploratory data analysis (EDA)
- Python project organization
- Data visualization
- Modular programming

The original notebook-based workflow was progressively refactored into reusable Python modules to improve code readability, maintainability and reproducibility.

---

# Author

Sichao Jing  
Mathematics & Economics Student — Université Paris-Saclay

