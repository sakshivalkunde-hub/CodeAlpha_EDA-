# CodeAlpha Data Analytics Internship
## Task 2: Exploratory Data Analysis (EDA) on Titanic Dataset

## Project Overview
This project was completed as part of the **CodeAlpha Data Analytics Internship**. The objective of this project is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset using Python. The analysis focuses on understanding the dataset, identifying missing values, exploring relationships between variables, and creating meaningful visualizations to gain useful insights.

## Dataset
- **Dataset Name:** Titanic Dataset (CSV)
- **Total Records:** 891
- **Total Columns:** 12
- **Source:** Kaggle - Titanic Dataset

## Tools & Technologies Used
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

## Project Structure

```
CodeAlpha_EDA/
│── CodeAlpha_EDA.ipynb
│── titanic.csv.csv
└── README.md
```

## Tasks Performed
- Imported the required Python libraries.
- Loaded the Titanic dataset.
- Explored the dataset using:
  - `head()`
  - `info()`
  - `describe()`
- Checked for missing values using `isnull().sum()`.
- Created visualizations to understand the data.
- Analyzed survival patterns based on gender, age, and passenger class.
- Generated a correlation heatmap to understand relationships between numerical features.

## Visualizations
- Survival Count Plot
- Survival by Gender
- Age Distribution
- Passenger Class Distribution
- Correlation Heatmap

## Key Findings
- The dataset contains **891 passenger records** and **12 columns**.
- Missing values were found in the **Age**, **Cabin**, and **Embarked** columns.
- Female passengers had a significantly higher survival rate than male passengers.
- Most passengers traveled in **Third Class (Pclass 3)**.
- The majority of passengers were between **20 and 40 years** of age.
- The correlation heatmap helped identify relationships between numerical variables.

## Conclusion
This project demonstrates how Exploratory Data Analysis (EDA) can be used to understand a dataset before applying machine learning or statistical models. Using Python libraries such as Pandas, Matplotlib, and Seaborn, meaningful insights were extracted through data exploration and visualization.

## Author
**Sakshi Valkunde**

**CodeAlpha Data Analytics Intern**