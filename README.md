Will the Customer Accept the Coupon?

General Overview:

The dataset contains 26 columns with 12,684 rows, which include attributes such as destination, passanger, weather, time, coupon type, expiration, gender, age, marital status, and several others.
Missing Data:

The dataset has missing values in several columns:
car: 12,576 missing values
Bar: 107 missing values
CoffeeHouse: 217 missing values
CarryAway: 151 missing values
RestaurantLessThan20: 130 missing values
Restaurant20To50: 189 missing values
It's important to address these missing values before conducting any further analysis or modeling. Possible approaches include imputation, deletion, or understanding the reason for missingness.
Data Types:

The dataset has a mix of data types. Most of the columns are of the object type (categorical), while some are of the int64 type. Specifically:
Object: Such as destination, passanger, weather, time, gender, age, etc.
Integer: temperature, has_children, toCoupon_GEQ5min, direction_same, Y, etc.
Duplicates:

There are 74 duplicated rows in the dataset. It's crucial to consider removing these duplicates, especially if they don't offer any unique information.
Statistical Summary:

Temperature has values ranging from 30 to 80 with an average of approximately 63.3.
The has_children column suggests that about 41.4% of the dataset's rows pertain to people with children.
The toCoupon_GEQ5min column has a constant value of 1 for all rows.
About 56.8% of the entries in the Y column have a value of 1, indicating a slight imbalance.
Methods
Explanation of the methods used:

Tools Used: Python (Pandas for data wrangling, Matplotlib & Seaborn for visualization, Scikit-Learn for machine learning)

Techniques:

Data Cleaning: Handled missing values and removed duplicates.
Exploratory Data Analysis (EDA): Visualized distributions, correlations, and patterns in the data.
Encoding: Converted categorical data into numerical form using one-hot encoding and label encoding for machine learning.


Link to Jupyter Notebook: Notebook Name

