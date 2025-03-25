# Intermediate Phase Submission - Bank Marketing Campaign Analysis

## Project Overview

This project aims to analyze data from a bank marketing campaign using machine learning techniques. The dataset contains customer details and information about past marketing efforts. The objective of this phase is to explore the dataset and perform preliminary data analysis.

## Tasks Completed in the Intermediate Phase

### 1. Load the Dataset

The dataset is loaded using pandas.  
File path: bank-full.xlsx

### 2. Show Dataset Shape

The dataset contains 45,211 rows and 17 columns.  
Command used: df.shape

### 3. Describe Statistical Summaries

Used df.describe() to get an overview of numerical columns.  

### 4. Check Skewness

Calculated skewness for numerical columns using df.skew(numeric_only=True).  
Used seaborn to visualize distributions of key features (balance, duration, campaign, etc.).

### 5. Detect Outliers Using a Box Plot

Plotted box plots using matplotlib and seaborn.  
Identified potential outliers in balance, duration, campaign, and previous.
