# Task 12: Missing Value Identification

## Project Overview
This project focuses on identifying and summarizing missing values in the Titanic dataset using Python and Pandas. It demonstrates basic missing-data inspection and explains why missing values should be investigated before deciding how to handle them.

## Objectives
- Identify missing values in each column.
- Calculate missing-value counts and percentages.
- Sort columns by the number of missing values.
- Summarize findings and understand the risks of blindly deleting data.

## Tools and Technologies
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Excel

## Dataset
The Titanic dataset contains 891 rows and 15 columns.

## Key Findings
- Total missing cells: 869
- Columns containing missing values: 4
- `deck`: 688 missing values (77.22%)
- `age`: 177 missing values (19.87%)
- `embarked`: 2 missing values (0.22%)
- `embark_town`: 2 missing values (0.22%)
- Remaining 11 columns: No detected missing values

## Methodology
1. Loaded the dataset using Pandas.
2. Inspected its structure and dimensions.
3. Counted missing values using `isnull().sum()`.
4. Calculated missing percentages.
5. Created and sorted a missing-value summary table.
6. Documented findings without deleting or modifying any values.

## Key Learning
Missing values should not be removed blindly. Their causes, importance, and potential impact on analysis should be considered before choosing a suitable treatment method.

## Deliverables
- Missing-value summary
- Short findings
- Interview questions and answers

## Conclusion
This project demonstrates how to identify and summarize missing data systematically. The results highlight the `deck` and `age` columns as the main areas requiring further investigation before any data-cleaning decisions are made.

**Internship Task:** VEDA Technology — Task 12  
**Author:** Tehreem Fatima
