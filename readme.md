This repository contains a beginner-friendly practice notebook focused on **Pandas for data processing and analysis**.  
It demonstrates how to create, inspect, analyze, and manipulate Pandas DataFrames using real datasets.

## Topics Covered

### 1. Introduction to Pandas
- Pandas library overview
- Understanding what a DataFrame is (2D tabular structure with rows and columns)

### 2. Creating DataFrames
- Creating a DataFrame from a dataset using `sklearn`
- California Housing dataset loaded using `fetch_california_housing`
- Converting dataset into a Pandas DataFrame
- Viewing first few rows using `.head()`
- Checking DataFrame shape

### 3. Importing Data from CSV
- Loading a CSV file using `pd.read_csv()`
- Diabetes dataset as an example
- Checking DataFrame type and shape

### 4. Exploring DataFrames
- Viewing column-wise data using `.head()`
- Checking dataset information using `.info()`
- Finding missing values with `.isnull().sum()`

### 5. Data Analysis
- Counting specific label values using `.value_counts()`
- Grouping data using `.groupby()`
- Calculating mean values by group

### 6. Statistical Operations
- Mean of columns
- Standard deviation
- Minimum and maximum values
- Complete statistical summary using `.describe()`

### 7. DataFrame Manipulation
- Dropping rows using `.drop()`
- Dropping columns
- Selecting rows using `.iloc`
- Selecting specific columns using index positions

