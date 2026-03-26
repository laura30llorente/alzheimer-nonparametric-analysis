# Alzheimer’s Disease Analysis using Non-Parametric Statistical Methods

## Overview

This project presents a comprehensive statistical analysis of Alzheimer’s disease data using non-parametric inference techniques. The goal is to identify significant relationships between clinical, demographic and lifestyle variables and the presence of Alzheimer’s disease, without assuming underlying probability distributions.

This approach is particularly suitable for medical datasets, where normality assumptions are often violated.

---

## Objectives

* Identify variables significantly associated with Alzheimer’s diagnosis
* Apply and interpret non-parametric statistical tests
* Compare groups based on clinical and demographic features
* Extract meaningful insights from real-world medical data

---

## Dataset description

Link: https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset

The dataset contains clinical, demographic and behavioral variables related to patients, including:

* Age
* Gender
* Cognitive and functional scores
* Lifestyle factors
* Medical conditions

The target variable indicates whether a patient has Alzheimer’s disease.

---

## Methodology

### 1. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Feature selection and transformation
* Creation of derived variables where necessary


### 2. Exploratory Data Analysis (EDA)

* Distribution analysis of variables
* Group comparisons (Alzheimer vs Non-Alzheimer)
* Visualization of key variables using histograms, boxplots and bar charts


### 3. Non-Parametric Statistical Tests

Due to the absence of normality in many variables, the analysis relies on non-parametric methods:

#### Mann-Whitney U Test

* Used to compare two independent groups
* Applied to continuous variables (e.g., age, clinical scores)
* Objective: determine whether distributions differ significantly between Alzheimer and non-Alzheimer groups

#### Kruskal-Wallis Test

* Extension of Mann-Whitney for more than two groups
* Used for categorical variables with multiple levels
* Objective: detect differences across multiple categories

#### Chi-Square Test of Independence

* Applied to categorical variables
* Objective: evaluate dependency between variables and Alzheimer diagnosis

---

## Statistical analysis and comparisons

For each variable, the following steps were performed:

1. Definition of null and alternative hypotheses
2. Selection of appropriate statistical test
3. Computation of test statistic and p-value
4. Decision rule based on significance level (α = 0.05)
5. Interpretation of results in a medical context

Additionally:

* Variables were compared across groups
* Significant vs non-significant features were identified
* Patterns and relationships were analyzed

---

## Key results

* Identification of variables with statistically significant differences between groups
* Detection of dependencies between categorical variables and Alzheimer diagnosis
* Evidence of relevant clinical and demographic patterns

These findings support the importance of data-driven approaches in medical research.

---

## Interpretation

The results highlight how non-parametric methods provide robust insights when classical assumptions (such as normality) are not satisfied. This is particularly relevant in healthcare applications, where data variability is high.

---

## Technologies used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)
