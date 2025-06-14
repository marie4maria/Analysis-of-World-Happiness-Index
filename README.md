# World Happiness Index Analysis - Liberia, Ukraine, Congo

## 📊 Project Overview

In this project, we analyze the **World Happiness Report** data for three countries: **Liberia, Ukraine, and Congo**. The goal is to understand how various socio-economic factors contribute to the happiness scores of these countries, and perform statistical and regression analysis to interpret the results.

The World Happiness Report is based on survey data where respondents evaluate their current life situations on a scale of 0 to 10 (Cantril ladder). The happiness score is derived from this evaluation and decomposed into several contributing factors.

---

## 📁 Dataset Information

- **Source**: Gallup World Poll (2013-2016)
- **Columns Used**:
  - Happiness Score
  - GDP per Capita
  - Social Support
  - Healthy Life Expectancy
  - Freedom to Make Life Choices
  - Generosity
  - Perceptions of Corruption
  - Dystopia (Baseline value + Residual)
  
The dataset was preprocessed to select the three countries for focused analysis: **Liberia, Ukraine, Congo**.

---

## ⚙️ Technologies Used

- Python (Pandas, Matplotlib, scikit-learn, Statsmodels)
- Data Visualization
- Linear Regression Modeling

---

## 🔬 Analysis Performed

### 1️⃣ Descriptive Statistics

- Computed mean, min, max, standard deviation, and quartiles for the selected countries.

### 2️⃣ Visualization

- Bar plot of Happiness Scores
- Stacked bar chart to visualize factor-wise contribution
- Pie charts for:
  - GDP per Capita
  - Healthy Life Expectancy

### 3️⃣ Correlation Analysis

- Computed correlation of happiness score with all contributing factors.
- Observed:
  - Positive correlation with Social Support and Generosity
  - Negative correlation with GDP per capita, Life Expectancy, Freedom, and Corruption.

### 4️⃣ Regression Analysis

- Performed multiple linear regression using:
  - GDP per capita
  - Social support
  - Healthy life expectancy
  - Freedom to make life choices
  - Generosity
  - Perceptions of corruption
- Derived the following model:
