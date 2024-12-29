# Data-Analysis

## Overview
This project is a demonstration of the data analysis process from start to finish, with a focus on data wrangling and cleaning techniques. The notebook is designed to serve as a framework for data professionals, showing how to identify, clean, and analyze messy or dirty datasets effectively.

The dataset used in this project involves a clinical trial of patients undergoing treatment with two types of insulin, `Novodra` and `Auralin`. The data includes information about adverse reactions, treatment regimens, and patient demographics.

---

## Table of Contents
1. [Project Framework](#project-framework)
2. [Dataset Description](#dataset-description)
3. [Key Features](#key-features)
4. [How to Use](#how-to-use)
5. [Requirements](#requirements)

---

## Project Framework
The steps involved in the project include:
1. **Data Wrangling**
   - Data Gathering
   - Data Assessing
   - Data Cleaning
2. **Exploratory Data Analysis (EDA)**
   - Visualizing Patterns
   - Generating Insights
3. **Drawing Conclusions**
   - Answering the Research Questions
4. **Communicating Results**
   - Presenting findings through visuals and summaries.

---

## Dataset Description
The project uses the following datasets:
- **Patients.csv**: Contains demographic and clinical information for 500+ patients.
- **Treatments.csv**: Includes details about treatment regimens and outcomes.
- **Adverse_Reactions.csv**: Lists adverse effects experienced by patients during the trial.
- **Treatments_Cut.csv**: A smaller, cleaned version of the treatments dataset.

### Key Columns:
- `patient_id`: Unique identifier for each patient.
- `assigned_sex`: Assigned sex at birth.
- `bmi`: Body Mass Index, indicating health conditions.
- `hba1c_start` & `hba1c_end`: Baseline and final HbA1c levels during treatment.
- `dosage_start` & `dosage_end`: Insulin dosage levels at the start and end of the trial.

---

## Key Features
- Identification and resolution of common data quality issues:
  - **Dirty Data**: Duplicates, missing data, invalid values.
  - **Messy Data**: Incorrect column formatting, unstructured values.
- Consolidation of datasets through merging.
- Programmatic assessment using Python (`pandas` and `numpy`).
- Creation of calculated fields like HbA1c change for better analysis.
- Application of advanced string operations and regex for data cleaning.

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Data-Analysis.git


##Acknowledgments
The dataset used in this project is fictional and inspired by real-world clinical trials. This project is intended for educational purposes to demonstrate data wrangling and analysis.
