# Layoffs Data Analysis Project

## Overview
Data cleaning and exploratory data analysis (EDA) 
project using SQL on a real-world layoffs dataset.

## Project Stages

### 1. Data Cleaning
- Removed duplicates using ROW_NUMBER()
- Standardized data (TRIM, date format, industry names)
- Handled NULL values using self JOIN
- Removed irrelevant rows

### 2. Exploratory Data Analysis (EDA)
- Analyzed layoffs by company, industry, and country
- Identified top 5 companies per year using DENSE_RANK()
- Calculated rolling total of layoffs using CTE

## Tools
- MySQL
- MySQL Workbench

## Dataset
- Source: Kaggle - Layoffs Dataset
