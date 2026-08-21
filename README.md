# 🌍 Top 10 Most Populated Countries – 2025

## 📌 Project Overview

This project analyzes population data and visualizes the **Top 10 most populated countries in 2025** using Python.

The project uses **Pandas** for data processing and **Matplotlib** for data visualization.  
The dataset is filtered using **PyCountry** to ensure that only actual countries are included and regional/aggregate entries such as "World", "OECD Members", and "South Asia" are excluded.

---

## 🎯 Objective

The main objective of this project is to:

- Load and explore population data
- Clean and preprocess the dataset
- Identify valid countries using ISO country codes
- Find the Top 10 countries by population
- Create a professional bar chart
- Save the visualization as an image

---

## 🛠️ Technologies Used

- 🐍 Python
- 🐼 Pandas
- 📊 Matplotlib
- 🌍 PyCountry
- ☁️ Google Colab
- 🗃️ World Bank Population Dataset

---

## 📂 Dataset

The dataset contains population information for countries and regions from **1960 to 2025**.

### Important Columns

| Column | Description |
|---|---|
| Country Name | Name of the country or region |
| Country Code | ISO-3 country code |
| Indicator Name | Population indicator |
| 2025 | Population in 2025 |

---

## 🔄 Project Workflow

```text
Dataset
   ↓
Load CSV File
   ↓
Data Cleaning
   ↓
Select Required Columns
   ↓
Validate Country Codes
   ↓
Filter Actual Countries
   ↓
Sort by Population
   ↓
Select Top 10
   ↓
Create Bar Chart
   ↓
Save Visualization
