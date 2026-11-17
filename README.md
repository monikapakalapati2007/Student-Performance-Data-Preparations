# Student Performance Data Preparation

## Project Overview
This project focuses on preparing two student performance datasets for machine learning and data analysis.

## Datasets
1. Student Performance in Exams – 1,000 records.
2. Student Performance 1 Million – 1,000,000 records.

## Data Preparation
- Loaded datasets using Pandas.
- Checked dataset structure and missing values.
- Split datasets into training, validation, and testing sets.
- Used a 70:15:15 split ratio.
- Used random_state=42.
- Applied stratification by grade to the million-record dataset.
- Converted datasets into Parquet format.

## Output Files
- exams_train.parquet
- exams_validation.parquet
- exams_test.parquet
- million_train.parquet
- million_validation.parquet
- million_test.parquet

## Hugging Face Dataset
[View the six Parquet files](https://huggingface.co/datasets/monika-p/students-performance-splits)

## Technologies Used
Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn, PyArrow, Hugging Face, GitHub.

## Split Ratio
- Training: 70%
- Validation: 15%
- Testing: 15%
