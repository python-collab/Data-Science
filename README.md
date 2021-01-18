# *Project 1- Retail Analysis with Walmart Data*

## Dataset Description

This is the historical data that covers sales from 2010-02-05 to 2012-11-01, in the file Walmart_Store_sales. Within this file you will find the following fields:

Store - the store number
Date - the week of sales
Weekly_Sales -  sales for the given store
Holiday_Flag - whether the week is a special holiday week 1 – Holiday week 0 – Non-holiday week
Temperature - Temperature on the day of sale
Fuel_Price - Cost of fuel in the region
CPI – Prevailing consumer price index
Unemployment - Prevailing unemployment rate

Holiday Events
Super Bowl: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13
Labour Day: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13
Thanksgiving: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13
Christmas: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13

# Analysis Tasks- Basic Statistics tasks

### 1. Which store has maximum sales
### 2. Which store has maximum standard deviation i.e., the sales vary a lot. Also, find out the coefficient of mean to standard deviation
### 3. Which store/s has good quarterly growth rate in Q3’2012
### 4. Some holidays have a negative impact on sales. Find out holidays which have higher sales than the mean sales in non-holiday season for all stores together
### 5. Provide a monthly and semester view of sales in units and give insights

# Statistical Model-

### For Store 1 – Build  prediction models to forecast demand
Linear Regression – Utilize variables like date and restructure dates as 1 for 5 Feb 2010 (starting from the earliest date in order). Hypothesize if CPI, unemployment, and fuel price have any impact on sales.
Change dates into days by creating new variable. Select the model which gives best accuracy.

*-> Detailed Analsyis and coding with statistical model are provided in Walmart Retail Data Analysis.ipynb file

# *Project 2- IBM HR Analytics Employee Attrition Modeling*

    IBM is an American MNC operating in around 170 countries with major business vertical as computing, software, and hardware.
    Attrition is a major risk to service-providing organizations where trained and experienced people are the assets of the company. The organization would like to identify       the factors which influence the attrition of employees.
    Data Dictionary
    Age: Age of employee
    Attrition: Employee attrition status
    Department: Department of work
    DistanceFromHome
    Education: 1-Below College; 2- College; 3-Bachelor; 4-Master; 5-Doctor;
    EducationField
    EnvironmentSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;
    JobSatisfaction: 1-Low; 2-Medium; 3-High; 4-Very High;
    MaritalStatus
    MonthlyIncome
    NumCompaniesWorked: Number of companies worked prior to IBM
    WorkLifeBalance: 1-Bad; 2-Good; 3-Better; 4-Best;
    YearsAtCompany: Current years of service in IBM

## Analysis Task:
    - Import attrition dataset and import libraries such as pandas, matplotlib.pyplot, numpy, and seaborn.
    - Exploratory data analysis
    ### 1. Find the age distribution of employees in IBM
    ### 2. Explore attrition by age
    ### 3. Explore data for Left employees
    ### 4. Find out the distribution of employees by the education field
    ### 5. Give a bar chart for the number of married and unmarried employees
    ### 6. Build up a logistic regression model to predict which employees are likely to attrite.

# *Project 3- House Sales Prediction*
    Use Linear regression and Gradient Boost algorithm to check the accuracy of model and answer the below questions-
    ### 1. Which is the most common house (Bedroom wise) ?
    ### 2. Visualizing the location of the houses based on latitude and longitude.
    ### 3. How common factors are affecting the price of the houses ?

# *Project 4- Mushroom Classification problem*
     1. What types of machine learning models perform best on this dataset?
     2. Which features are most indicative of a poisonous mushroom?

# *Project 5- Store Item Demand Forecast (TIME SERIES)*
    1. You are given 5 years of store-item sales data, and asked to predict average sales for different items at different stores.
    2. Identify the average sales by Stores and Items
  
# *Project 6- Comcast Telecom Consumer Complaints*
  1. Use any of the different Python libraries such as NumPy, SciPy, Pandas, scikit-learn, matplotlib, and BeautifulSoup-
   - Import data into Python environment.
   - Provide the trend chart for the number of complaints at monthly and daily granularity levels.
   - Provide a table with the frequency of complaint types.

  2. Which complaint types are maximum i.e., around internet, network issues, or across any other domains.
   - Create a new categorical variable with value as Open and Closed. Open & Pending is to be categorized as Open and Closed & Solved is to be categorized as Closed.
   - Provide state wise status of complaints in a stacked bar chart. Use the categorized variable from Q3. Provide insights on:

  3. Which state has the maximum complaints
  4. Which state has the highest percentage of unresolved complaints
   - Provide the percentage of complaints resolved till date, which were received through the Internet and customer care calls.
 
 # *Project 7- Movielens Case Study*
   1. Import the three datasets
   2. Create a new dataset [Master_Data] with the following columns MovieID Title UserID Age Gender Occupation Rating. (Hint: (i) Merge two tables at a time. 
      (ii) Merge the  tables using two primary keys MovieID & UserId)
   3. Explore the datasets using visual representations (graphs or tables), also include your comments on the following:
      - User Age Distribution
      - User rating of the movie “Toy Story”
      - Top 25 movies by viewership rating
      - Find the ratings for all the movies reviewed by for a particular user of user id = 2696
    4. Feature Engineering:
       Use column genres:
      - Find out all the unique genres (Hint: split the data in column genre making a list and then process the data to find out only the unique categories of genres)
      - Create a separate column for each genre category with a one-hot encoding ( 1 and 0) whether or not the movie belongs to that genre. 
      - Determine the features affecting the ratings of any particular movie.
      - Develop an appropriate model to predict the movie ratings
 
   
