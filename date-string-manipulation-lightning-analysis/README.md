# ⚡ Lightning Strikes Data Analysis with Date String Manipulation (Python & Pandas)

## 📌 Project Overview

In this notebook, we will work with 2016–2018 lightning strike data from the National Oceanic 
and Atmospheric Association (NOAA) to calculate weekly sums of lightning strikes and plot them on a bar graph.
Then, we will calculate quarterly lightning strike totals and plot them on bar graphs.

This project demonstrates data cleaning, date string manipulation, feature engineering, data aggregation, and visualization using Python, Pandas, Matplotlib, and Seaborn.

The original lightning strike dataset was very large, so a new dataset containing **50,000 randomly sampled records** 
was created for efficient analysis while preserving the overall data distribution.

### For orignal data here's Google_drive link
https://drive.google.com/file/d/1yeJPZDUVbdW2-hvyyka_pZuLNxoZZh4W/view?usp=sharing

### Orignal dataset image
![Image] <img width="577" height="585" alt="orignal dataset " src="https://github.com/user-attachments/assets/cb768eee-75b2-4cba-abbb-473da71ceebb" />



---

## 🎯 Project Objectives

* Create a manageable dataset from the original large dataset
* Perform date string manipulation and datetime conversion
* Extract time-based features from dates
* Analyze lightning strike trends over different time periods
* Create informative visualizations for data insights

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Project Workflow

### 1️⃣ Check Original Dataset Size

Examined the size and structure of the original lightning strike dataset.

### 2️⃣ Create Random Sample

Generated a random sample of **50,000 rows** from the original dataset.

### 3️⃣ Verify Sample Size

Validated that the new dataset contains exactly 50,000 records.

### 4️⃣ Save New Dataset

Exported the sampled data into a new CSV file.

### 5️⃣ Load Sample Dataset

Loaded the newly created CSV file for analysis.

### 6️⃣ Date Conversion

Converted the `date` column from string format to Pandas datetime format.

### 7️⃣ Feature Engineering

Created four new date-based columns:

* Week
* Month
* Quarter
* Year

These features enabled time-series analysis at multiple levels.

---

## 📊 Exploratory Data Analysis

### Weekly Lightning Strikes in 2018
![Weekly] <img width="1118" height="349" alt="weeklylightning strikes in 2018" src="https://github.com/user-attachments/assets/90c95002-abe9-4815-a33c-28f6df3341b3" />



* Filtered data for 2018
* Grouped lightning strikes by week
* Calculated weekly strike totals
* Created a bar chart showing weekly lightning activity throughout the year

### Quarterly Lightning Strikes (2016–2018)
![Quarterly]<img width="1096" height="406" alt="Quarterly Lightning Strikes (2016–2018)" src="https://github.com/user-attachments/assets/6ec1c999-9ffb-4dbb-a2c2-1976f48d3131" />

* Aggregated lightning strikes by quarter
* Compared trends across multiple years
* Visualized quarterly strike patterns using bar charts

###  Number of lightning strikes per quarter
![Bar Chart]<img width="1097" height="410" alt="Number of lightning strikes per quarter" src="https://github.com/user-attachments/assets/e81a6084-bc33-4704-af28-af0f8ae05b7d" /> 


Created grouped bar charts to compare:

* Lightning activity across years
* Quarterly trends
* Seasonal variations

---

## 📈 Key Skills Demonstrated

✅ Data Cleaning

✅ Random Sampling

✅ CSV File Handling

✅ Datetime Conversion

✅ Date String Manipulation

✅ Feature Engineering

✅ Data Aggregation

✅ Data Visualization

✅ Time Series Analysis

✅ Exploratory Data Analysis (EDA)

---

## 📷 Visualizations Included

* Weekly Lightning Strikes (2018)
* Quarterly Lightning Strikes (2016–2018)
* Grouped Bar Charts for Yearly Comparison

---

## 🚀 Learning Outcomes

Through this project, I gained hands-on experience with:

* Working with large datasets
* Creating representative samples
* Manipulating date and time data
* Performing time-based aggregations
* Building professional data visualizations
* Extracting meaningful insights from real-world datasets

---

## 📁 Dataset

A 50,000-row sampled dataset was created from the original lightning strike dataset and used throughout the analysis.

---

## 👩‍💻 Author

**Mehwish Iqbal**

Aspiring Data Analyst | Python | Pandas | Data Visualization | Data Analytics
