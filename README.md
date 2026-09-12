# Heart Disease Analysis

An exploratory data analysis project using Python and Power BI to investigate factors associated with heart disease in the UCI Heart Disease dataset.

## Project Overview

This project explores patient characteristics and their relationship with heart disease status. The analysis focuses on identifying patterns across demographic, clinical, and exercise-related features and presenting the findings through an interactive Power BI dashboard.

The project was developed to strengthen practical data analysis skills, including data cleaning, exploratory analysis, feature relationships, and business-style data visualization.

## Objectives

* Explore the structure and quality of the dataset.
* Analyze the distribution of heart disease status.
* Investigate heart disease rates across age groups, sex, and chest pain types.
* Compare clinical measurements between patients with and without heart disease.
* Examine relationships between selected features and the target variable.
* Build an interactive dashboard to communicate the findings.

## Dataset

The dataset is the Heart Disease dataset from the UCI Machine Learning Repository.

* **Source:** [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
* **Number of records:** 303
* **Number of features:** 13
* **Target variable:** Heart disease status

The dataset includes demographic information, clinical measurements, chest pain type, exercise-related features, and other diagnostic attributes.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Power BI

## Project Workflow

### 1. Data Loading and Exploration

* Loaded the dataset using Pandas.
* Inspected the dataset structure, data types, and dimensions.
* Reviewed descriptive statistics.

### 2. Data Quality Assessment

* Checked for missing values.
* Investigated duplicate records.
* Examined potential outliers in numerical features.
* Retained medically plausible values during exploratory analysis.

### 3. Exploratory Data Analysis

The analysis includes:

* Heart disease distribution.
* Heart disease rate by age group.
* Patient distribution by sex.
* Heart disease rate by chest pain type.
* Comparison of average cholesterol, resting blood pressure, and maximum heart rate by disease status.
* Exercise-induced angina analysis.
* Exploratory feature correlation analysis.

### 4. Power BI Dashboard

An interactive dashboard was created to present the analysis in a clear and accessible format.

Dashboard components include:

* Key performance indicators.
* Interactive filters.
* Disease rate by age group.
* Patient distribution by sex.
* Disease rate by chest pain type.
* Clinical measurement comparisons.
* Exercise-induced angina analysis.
* Feature correlation visualization.

## Key Findings

The exploratory analysis identified several patterns in this dataset:

* 303 patient records were analyzed.
* 165 records had a positive heart disease target, while 138 had a negative target.
* Chest pain type, maximum heart rate, and exercise-related features showed notable associations with the target variable.
* Some numerical variables contained potential outliers that were retained because they were not automatically treated as invalid medical measurements.

These findings describe patterns in the dataset and should not be interpreted as medical diagnoses or causal relationships.

## Limitations

* The dataset contains a relatively small number of records.
* The analysis is exploratory and does not establish causation.
* Correlation coefficients involving numerically encoded categorical variables should be interpreted carefully.
* The results are specific to this dataset and should not be generalized to the wider population.
* The project does not provide a clinically validated diagnostic model.

## Conclusion

This project demonstrates a complete exploratory data analysis workflow, from data quality assessment and statistical exploration to interactive dashboard development.

It was created as part of my data analytics portfolio to improve my ability to transform raw data into meaningful insights and communicate analytical findings through visualizations.
