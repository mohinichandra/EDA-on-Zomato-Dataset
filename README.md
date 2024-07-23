# EDA-on-Zomato-Dataset
## Project Overview
The Zomato Dataset EDA (Exploratory Data Analysis) project aims to uncover insights and trends within the Zomato dataset using Python and popular data analysis libraries. The steps involved in the project include data cleaning, preprocessing, and visualization to draw meaningful conclusions about various aspects of restaurant data.

## Libraries and Tools Used
#### 1. Python: 
The core programming language used for data manipulation and analysis.
#### 2. Pandas: 
Utilized for data manipulation and preprocessing tasks.
#### 3. Numpy: 
Used for numerical operations.
#### 4. Matplotlib: 
Employed for creating static visualizations.
#### 5. Seaborn: 
Used for creating more advanced and aesthetically pleasing visualizations.

## Steps Performed
### 1. Data Cleaning
#### Dropping Unnecessary Columns:
Columns that do not contribute to the analysis were removed.
#### Dropping Duplicates: 
Duplicate records were identified and removed to ensure data integrity.
#### Cleaning Columns:
Columns were formatted, and data types were corrected as needed.
#### Filling Null Values:
Missing values were handled appropriately, either by filling them with relevant data or by removing rows/columns with excessive missing data.

## 2. Data Visualization
Visualization plays a crucial role in understanding the distribution and relationships within the dataset. The following visualizations were created:

#### a. Countplot for Location Popularity: 
Visualized the frequency of restaurants in different locations to identify popular areas.

#### b. Countplot for Online Order (Yes/No): 
Displayed the count of restaurants offering online ordering versus those that do not.

#### c. Countplot for Book Table (Yes/No):
Showed the count of restaurants that allow table booking versus those that do not.

#### d. Boxplot for Online Order vs Rate:
Analyzed the relationship between online ordering availability and restaurant ratings.

#### e. Boxplot for Book Table vs Rate: 
Examined the impact of table booking availability on restaurant ratings.

#### f. Pivot Table and Barplot for Online Order Facility, Location Wise: 
Created a pivot table to analyze the availability of online ordering by location and visualized it using a bar plot.

#### g. Pivot Table and Barplot for Book Table Facility, Location Wise: 
Similar to the above, but for table booking availability.

#### h. Boxplot for Types of Restaurants vs Rate: 
Investigated the relationship between different types of restaurants and their ratings.

#### I. Bar Plot for Types of Restaurants, Location Wise: 
Visualized the distribution of different types of restaurants across various locations.

