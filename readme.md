# Data Lifecycle – From Collecting to Archiving

This is a simple student project that demonstrates basic stages of the data lifecycle using a synthetic smartwatch health dataset. It includes steps such as loading, exploring, cleaning, transforming, and archiving data.

## Project Overview

The main objective is to walk through a typical data lifecycle by covering:

1. Data loading
2. Inspecting data
3. Data cleaning
4. Exporting and archiving cleaned data 

All steps are documented and executed in a Jupyter Notebook (`smartwatch_data_lifecycle.ipynb`).

The project was created for educational purposes as part of a university assignment.

### Tools Used

- Python 3
- Jupyter Notebook
- pandas
- zipfile
- matplotlib and seaborn (basic plotting)

## About Dataset - Smartwatch Health Data

The dataset used in this project is publicly available on Kaggle and was designed for educational purposes.
It simulates health-related data collected by a smartwatch and includes common real-world data issues such as missing values, outliers, duplicates, and inconsistencies. The data was synthetically generated using Python's numpy and pandas libraries.

The dataset consists of following columns:

- **User ID** - Unique ID for each smartwatch user
- **Heart Rate (BPM)** - User’s heart rate in beats per minute
- **Blood Oxygen Level (%)** - Percentage of oxygen saturation in the blood
- **Step Count** - Number of steps taken per day
- **Sleep Duration (hours)** - Total sleep duration in hours
- **Activity Level** - Categorized as Sedentary, Active, or Highly Active
- **Stress Level** - Subjective stress rating from 1 to 10

### Dataset Summary
- **Rows:** 10,000  
- **Columns:** 7  
- **Use Case:** Health monitoring with smartwatch sensor data  
- **Source:** [Kaggle – Smartwatch Health Data (Uncleaned)](https://www.kaggle.com/datasets/mohammedarfathr/smartwatch-health-data-uncleaned)  
- **License:** Apache License 2.0

