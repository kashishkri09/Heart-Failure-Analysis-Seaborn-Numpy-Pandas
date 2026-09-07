# ❤️ Heart Disease Data Analysis & Visualization

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** and **Data Visualization** on a Heart Disease dataset using Python.

The main goal of this project is to understand the dataset, identify patterns and relationships between different health-related features, and visualize important insights using various plots.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## 📊 Dataset

The dataset contains information about patients and several health-related attributes, such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Maximum Heart Rate
* Heart Disease

## 🔍 Exploratory Data Analysis

### 1. Age Distribution

A distribution plot/histogram was used to understand the distribution of patients across different age groups.

### 2. Categorical Data Analysis

Pie charts were used to visualize categorical variables such as:

* Gender
* Chest Pain Type
* Heart Disease

### 3. Violin Plot

Violin plots were used to understand the distribution of numerical variables across different categories.

Examples include:

* Age
* Cholesterol
* Resting Blood Pressure
* Maximum Heart Rate

### 4. Correlation Analysis

The `corr()` function was used to calculate correlations between numerical features.

A **heatmap** was created using Seaborn to visualize these correlations.

```python
df.corr(numeric_only=True)
```

### 5. Joint Plot

Joint plots were used to study relationships between two numerical variables, such as:

* Age vs Maximum Heart Rate
* Heart Disease vs Maximum Heart Rate

### 6. Pair Plot

A pair plot was created to visualize relationships between multiple numerical features simultaneously.

## 📈 Key Insights

The analysis helps in understanding:

* Distribution of patients by age and gender.
* Distribution of heart disease cases.
* Relationship between different health-related features.
* Correlation between numerical variables.
* Patterns between age, cholesterol, blood pressure and maximum heart rate.

## 🎯 Conclusion

This project demonstrates how **Exploratory Data Analysis and Data Visualization** can be used to understand a real-world healthcare dataset.

Different visualization techniques such as **histograms, pie charts, violin plots, heatmaps, joint plots and pair plots** provide useful insights into the relationships and distributions within the dataset.

## 🚀 Future Scope

This analysis can be further extended by applying **Machine Learning classification algorithms** to predict whether a patient is likely to have heart disease.

---

⭐ If you find this project useful, feel free to explore the notebook and analysis.
