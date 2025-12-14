📊 Population Analysis in Ireland (2011–2022)
📌 Project Overview

This project performs an end-to-end data analysis of Ireland’s population using official census data from 2011, 2016, and 2022.
The objective is to explore demographic patterns by county, age group, sex, and year, applying data cleaning, exploratory data analysis (EDA), statistical methods, and data preparation techniques for machine learning.

The project was developed entirely in Python using Jupyter Notebook, following good programming and data analysis practices.

🧠 Key Objectives

Clean and standardise population datasets from different census years

Perform Exploratory Data Analysis (EDA) to identify trends and anomalies

Detect and analyse outliers by county and age group

Apply statistical distributions (Binomial, Normal) to real demographic scenarios

Explore correlations between demographic variables

Prepare data for machine learning workflows

🛠️ Technologies & Libraries

Python

Jupyter Notebook

NumPy

Pandas

Matplotlib

Seaborn

SciPy

Scikit-learn

📂 Dataset

The datasets include population records by:

Year (2011, 2016, 2022)

County

Age group

Sex

Population value

Extensive preprocessing was required to:

Unify county names

Merge split administrative regions (e.g. Limerick, Tipperary, Waterford)

Remove aggregated rows (Totals, Both Sexes, Ireland-level data)

Harmonise age ranges across datasets

🔍 Exploratory Data Analysis (EDA)

The EDA process includes:

Data type validation and cleaning

Removal of duplicates and irrelevant rows

Detection of outliers using IQR and boxplots

Population comparison by:

County

Age group

Sex

Year

Multiple visualisations (bar plots, scatter plots, histograms)

📈 Example insights:

Dublin consistently shows population outliers compared to other counties

Population distribution is right-skewed, not normally distributed

Age and population show a slight negative correlation

📐 Statistical Analysis

The project applies probability distributions to real-world demographic questions:

Binomial distribution for probability scenarios (e.g. probability of selecting a given number of males/females from the population)

Normal distribution analysis after logarithmic transformation

Discussion on why real population data often deviates from ideal normal distributions

🤖 Data Preparation for Machine Learning

To prepare the dataset for ML models:

Logarithmic transformation (log1p) to normalise population values

Encoding of categorical variables (County, Age, Sex)

Correlation analysis before and after transformation

Feature engineering using dummy variables

These steps ensure the dataset is suitable for regression or predictive modelling tasks.

📊 Visualisation Principles

All visualisations were designed following Tufts’ data visualisation principles, ensuring:

Clarity and readability

Meaningful comparison

Appropriate use of colour and scale

Insight-driven design

🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git


Open the notebook:

jupyter notebook


Run all cells in order to reproduce the analysis and visualisations.

📌 Project Status

✅ Completed
📘 Academic & portfolio project
🎯 Suitable for showcasing Data Analytics, Python, EDA, and Statistics skills

👤 Author

Erwin Plaza Copajira
MSc Data Analytics
📍 Ireland
