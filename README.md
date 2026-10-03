# SWYNEX Task 1 - Data Preparation

## Project Overview

This project was completed as part of the SWYNEX Technologies
internship Task 1 - Data Preparation.

The objective of this project is to prepare a public dataset
for data-science work by inspecting, cleaning, validating,
and exporting the dataset.

## Dataset

Titanic Passenger Dataset.

## Tools Used

- Python
- Pandas
- Google Colab
- GitHub

## Data Preparation Steps

1. Loaded the Titanic dataset using Pandas.
2. Inspected the dataset structure and columns.
3. Checked data types.
4. Identified missing values.
5. Checked duplicate records.
6. Handled missing Age values using the median.
7. Handled missing Embarked values using the mode.
8. Removed the Cabin column because of extensive missing data.
9. Performed final validation.
10. Exported the cleaned dataset as a CSV file.

## Assumptions

- Median was used for missing Age values.
- Mode was used for missing Embarked values.
- The Cabin column was removed because of extensive missing data.
- These choices were made for this basic data-preparation task.

## Validation

The cleaned dataset was checked for:

- Remaining missing values
- Duplicate records
- Data types
- Dataset shape
- Final column structure

## Files

- `SWYNEX_Task1_Data_Preparation.ipynb` - Complete Python notebook.
- `titanic_cleaned.csv` - Cleaned dataset.

## Conclusion

The Titanic dataset was successfully prepared for further
data analysis and machine-learning applications.

## Author

Shaik Sadiq Vaheeb
