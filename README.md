# 📱 google-playstore-data-stories
## Exploratory Data Analysis & Feature Engineering

---

## 📌 Project Overview

This project focuses on performing **Exploratory Data Analysis (EDA)** and **Feature Engineering** on the Google Play Store dataset.

The main objective was to:

- Clean messy real-world app data  
- Convert object columns into usable numeric formats  
- Analyze category distribution and install trends  
- Perform univariate analysis on categorical and numerical features  

This project helped me strengthen my understanding of data preprocessing and visualization using Python.

---

## 📂 Dataset Description

The dataset includes information about applications available on the Google Play Store, including:

- App Name  
- Category  
- Rating  
- Reviews  
- Size  
- Installs  
- Type (Free/Paid)  
- Price  
- Content Rating  
- Last Updated  
- Android Version  

---

## 🧹 Data Cleaning & Feature Engineering

The dataset contained inconsistent formats and special characters.  
The following preprocessing steps were performed:

- Checked and handled missing values  
- Removed duplicate entries  
- Cleaned special characters from numeric columns  
- Converted object columns into numeric format  

### Key Transformations:

- Cleaned **Installs** column (removed '+' and ',')  
- Cleaned **Price** column (removed '$')  
- Standardized **Size** column (converted M and K values)  
- Converted appropriate columns into numeric datatype  

---

# 📊 Exploratory Data Analysis

---

## 📈 1️⃣ Category Distribution (Pie Chart)

<img src="Images/most popular app category.png" width="750">

This visualization shows the distribution of apps across different categories in the Play Store.

---

## 📊 2️⃣ Most Popular Categories by Installations

<img src="Images/Most Popular Categories in Play Store.png" width="750">

This graph highlights the categories with the highest total installations.

---

## 📱 3️⃣ Top 5 Most Installed Apps in Popular Categories

<img src="Images/Top 5 most installed Apps in Each popular Categories.png" width="750">

This visualization shows the top installed apps within major categories such as:

- Game  
- Communication  
- Productivity  
- Social  

---

## 🔝 4️⃣ Top 10 App Categories

<img src="Images/Top 10 app Categories.png" width="750">

Displays the top 10 categories based on number of apps available.

---

## 📊 5️⃣ Univariate Analysis – Categorical Features

<img src="Images/Univariate Analysis of Categorical Features.png" width="750">

This section analyzes:

- Free vs Paid apps distribution  
- Content Rating distribution  

---

## 📊 6️⃣ Univariate Analysis – Numerical Features

<img src="Images/Univariate Analysis of Numerical Features.png" width="750">

This includes distribution analysis of:

- Rating  
- Reviews  
- Size  
- Installs  
- Price  
- Last Updated (Year, Month, Day)

---

## 🛠 Tools & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 📁 Project Structure

```
GooglePlayStore-EDA/
│
├── GooglePlaystore_Dataset.csv
├── EDA&FE.ipynb
├── Images/
│   ├── most popular app category.png
│   ├── Most Popular Categories in Play Store.png
│   ├── Top 5 most installed Apps in Each popular Categories.png
│   ├── Top 10 app Categories.png
│   ├── Univariate Analysis of Categorical Features.png
│   └── Univariate Analysis of Numerical Features.png
└── README.md
```

---

## 🎯 Key Learnings

Through this project, I learned:

- Handling real-world messy datasets  
- Data cleaning and preprocessing techniques  
- Converting object data to numeric format  
- Performing univariate analysis  
- Creating meaningful visualizations  
- Understanding app category and installation trends  

---
