# Python-Assess-the-Quality-of-a-Dataset-for-a-Public-Service-Agency

### Introduction

This repository contains the code and documentation for the data cleaning process of The tree within London Borough of Camden Council. 
The goal of this project is to clean and enhance the dataset which provides information
about a list of trees in the borough..

### Dataset Source and Overview

- **Trees Data**
A list of all the trees we have in the borough (both their location and types). This is an Excel file. 

- **Environmental Data**
lists all the trees and gives some environmental data about each tree. This is a csv file.

- **Common Names Data**
A list of scientific tree names and their matching common names.  this is json format. 

### Issues found in the data

During the initial exploration and analysis of the Council dataset, several issues were identified including:

- Missing values - Common Name column had missing values which required careful handling and computation.
- Inconsistent formatting - This was observed across different columns making it necessary to standardize the data
  for consistency.

### Tools Used

For the data cleaning project, the following tools and libraries were used:

1. **Python** for data cleaning tasks.
2. **Pandas** was instrumental in data manipulation, cleaning and handling missing values.
3. **matplotlib** was utilized for use a boxplot to show the spread of data and any outliers.
4. **Jupyter Notebooks** provided an interactive environment for code development, exploration and documentation.

### Data Cleaning Process

The data cleaning process involved the following steps:
1. **Data Understanding** - The dataset was thoroughly examined to understand the structure, columns and their meanings.
   The data did not have a data dictionary attached. With the help of online sources I was able to create one that helped me
   gain an understanding of what all the columns represented.
2. **Data Exploration** - Exploratory Data Analysis was performed to gain insights into the data, identify patterns and uncover anomalies.
3. **Validation and quality checks** - The cleaned dataset underwent rigorous validation to ensure the quality, accuracy and integrity of the data.

### Documentation

For detailed information about the data cleaning process, please refer to the Jupyter notebooks provided in the repository provided above.
They contain step by step explanations, code and documentation showing each stage of the data cleaning process.
