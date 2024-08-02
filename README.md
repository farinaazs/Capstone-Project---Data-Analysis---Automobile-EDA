# Automobile Exploratory Data Analysis (EDA)

### Overview
This repository contains an exploratory data analysis (EDA) of an automobile dataset. The goal of the analysis is to clean, sanitiSe, and explore the dataset to uncover insights related to various automobile attributes, such as vehicle make, fuel type, horsepower, price, and more. The analysis involves data cleaning, transformation, and visualisation techniques to help understand the relationships between different variables and answer key questions.

### Dataset
The dataset contains information about various automobile models, including details such as make, fuel type, aspiration, number of doors, body style, drive wheels, engine size, horsepower, and price. The dataset consists of 205 rows and 26 columns, which are reduced to 203 rows and 12 columns after cleaning and sanitisation.

### Analysis Steps
1. Data Cleaning:

* Remove unnecessary columns that are not needed for the analysis.
* Handle missing values represented by '?' by replacing them with appropriate values or removing affected rows.
* Convert data types of relevant columns from object to numeric where necessary.
* Replace categorical data with more descriptive values for better understanding.

2. Exploratory Data Analysis (EDA):

* Perform various data visualisations to understand the distribution and relationships between variables.
* Plot histograms, bar charts, and pie charts to visualise key attributes such as vehicle make, number of doors, drive wheels, fuel type, aspiration type, horsepower, city and highway MPG, price, normalised losses, and insurance risk ratings.
* Interpret the visualisations to draw meaningful insights and understand the dataset's structure.

### Visualisations

The EDA includes the following visualisations:
* Bar Charts: Distribution of vehicle makes, number of doors, drive wheels, fuel type, and price based on body style and number of doors.
* Pie Chart: Comparison of standard vs. turbocharged vehicles.
* Histograms: Distribution of horsepower, city and highway MPG, normalised losses, and insurance risk ratings.

### Results

The analysis provides insights into the most common vehicle makes, the distribution of fuel types, the relationship between price and body style, and other key factors affecting vehicle performance and cost.

### Tools Used

* Python: For data analysis and visualisation.
* Pandas: For data manipulation and cleaning.
* NumPy: For numerical operations.
* Matplotlib & Seaborn: For data visualisation.

### How to Run
1. Clone the repository.
2. Ensure you have Python installed along with the required libraries (numpy, pandas, matplotlib, seaborn).
3. Run the Jupyter notebook to reproduce the analysis.

--------------------------------------------------------------------------------------------------

#### References:
https://github.com/justinpolackal/eda-automobiles/blob/master/AutomobileDataSet_PrepareData.ipynb

https://www.kaggle.com/code/toramky/eda-for-automobile-dataset

#### Thank you, Farinaaz :)



