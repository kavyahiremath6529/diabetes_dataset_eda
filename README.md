# diabetes_dataset_eda
# Diabetes Dataset — Exploratory Data Analysis

## Project Overview
This project explores the Pima Indians Diabetes Dataset using Python. It focuses on understanding the dataset, checking data quality, visualizing feature distributions, and examining relationships between numerical features and the outcome variable.

## Objectives
- Understand the dataset structure and statistical properties.
- Check missing values and duplicate records.
- Investigate zero values in selected medical measurements.
- Perform data cleaning using median imputation.
- Visualize distributions and compare features across outcome groups.
- Explore correlations between numerical variables.

## Tools and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset
The dataset contains 768 records and 9 columns, including Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, and Outcome.

The notebook loads the dataset from a public GitHub CSV source.

## Project Workflow
1. Import libraries and load the dataset.
2. Inspect rows, columns, data types, and summary statistics.
3. Check missing values and duplicate records.
4. Investigate zero values in selected medical measurement columns.
5. Create a cleaned copy and fill identified missing measurements using median imputation.
6. Visualize feature distributions and diabetes outcomes.
7. Compare selected features by outcome and examine correlations.
8. Summarize findings and limitations.

## Key Findings
- The dataset contains 768 records and 9 columns.
- No duplicate rows were found in the initial dataset.
- Some selected medical measurement columns contain zero values that were investigated during preprocessing.
- Histograms, box plots, and a correlation heatmap were used to explore patterns in the data.

## How to Run
1. Open `diabetes_eda.ipynb` in GitHub or Google Colab.
2. Run the notebook cells in order.
3. Ensure an internet connection is available when loading the dataset from its public URL.

## Limitations
This project performs exploratory data analysis only; it does not build a diabetes prediction model or provide medical diagnoses. Treating zero measurements as missing values is a preprocessing assumption and may affect the results.

## Author
Kavya Hiremath
