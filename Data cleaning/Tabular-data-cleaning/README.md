# Tabular Data cleaning

1. Deal with duplicates, outliers and missing values
2. Encoding
3. Scalling and Normalization
4. Removing unwanted columns

&nbsp;

### 1. Duplicates, Outliers and Missing Values

This notebook demonstrates how to:

- Identify and remove duplicate records using `drop_duplicates()`
- Detect outliers using box plots and IQR (Interquartile Range) method
- Handle missing values through:
  - Deletion (dropping rows/columns)
  - Imputation (filling with zeros, mean, median, or values from adjacent rows)
- Evaluate the impact of missing data on your dataset

### 2. Encoding Categorical Variables

Covers techniques for converting categorical data to numerical formats:

- Ordinal encoding for categorical variables with inherent order
- One-hot encoding for nominal categorical variables
- Understanding when to use each encoding method based on data characteristics

### 3. Scaling and Normalization

Explains why feature scaling is important and demonstrates:

- Min-max scaling to transform features to a specific range (0-1)
- Other scaling techniques and when to apply them
- Impact of scaling on model performance

### 4. Removing Unwanted Columns

Shows methods for feature selection by:

- Identifying and removing low variance features
- Using `VarianceThreshold` from scikit-learn for automated feature selection
- Handling redundant or irrelevant features

&nbsp;

## Required Python libraries

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
