# NYC Green Taxi EDA using Pandas

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the NYC Green Taxi dataset using Python and Pandas.

The notebook demonstrates:
- Data loading and inspection
- Schema analysis
- Statistical summaries
- Missing value analysis
- Data cleaning
- Column removal
- Random sampling
- Basic exploratory techniques



## Technologies Used

- Python 3.11
- Pandas
- Jupyter Notebook
- VS Code



## Dataset

Dataset source:
NYC Green Taxi Open Dataset from Azure Open Datasets.



## Key EDA Steps

### Dataset Inspection
- Shape of dataset
- Column information
- Data types
- Row/column counts

### Statistical Analysis
- Summary statistics
- Fare amount analysis
- Trip distance insights

### Data Cleaning
- Removed unused columns
- Checked missing/null values
- Simplified dataframe

### Exploratory Analysis
- Unique categorical values
- Random sampling
- Data distribution exploration



## Sample Operations Performed

python \
df.info() \
df.describe() \
df.isnull().sum() \
df.sample(5) \
df.drop(columns=columns_to_remove)
