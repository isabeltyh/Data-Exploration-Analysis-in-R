# Teen Mental Health: Data Exploration & Analysis in R

## 📌 Project Overview
This was an individual academic project for **DCS1104: Introduction to Statistics and Data Analytics** at INTI International College Subang. 

The objective was to select a real-world dataset, clean the data, and generate visualisations using **R Studio** to extract actionable insights.

## The Dataset
*   **Name:** Teen Mental Health
*   **Source:** Kaggle (1,200 rows, 13 columns)
*   **Variables:** Age, gender, daily social media hours, platform usage, sleep hours, screen time before sleep, academic performance, physical activity, social interaction level, stress level, anxiety level, addiction level, and depression label.

## Technical Steps & R Implementation

**1. Data Exploration:**
Used `dim()`, `str()`, `summary()`, and `head()` to understand the dataset's structure and identify data types. 

**2. Data Cleaning:**
*   Checked for missing values using `sum(is.na(data))`. (No missing values were found).
*   Removed duplicate rows using `unique()`.
*   Converted character variables (gender, platform usage, social interaction, depression label) into factors using `as.factor()` to ensure accurate statistical analysis and chart generation.

**3. Data Visualisation:**
Created four distinct visualisations to analyze trends:
*   **Histogram:** Analyzed age distribution (found a balanced spread from ages 13-19).
*   **Bar Chart:** Visualized self-reported social interaction levels (categorized as low, medium, high).
*   **Boxplot:** Examined the distribution of sleep hours to spot the median and any outliers.
*   **Pie Chart:** Showed the proportional distribution of gender, confirming a balanced dataset for fair comparisons.

## Key Findings
The analysis highlighted clear connections between lifestyle factors and mental health. The data suggests that social media usage, sleep patterns, and social interaction levels are all connected to mental health indicators like stress and anxiety. Promoting healthy sleep habits and balanced social media use could potentially support better mental health outcomes for teenagers.

---
*Course: DCS1104 – Introduction to Statistics and Data Analytics | INTI International College Subang*
