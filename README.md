# Project Overview
In the following project, I am using python to analyze the cost of using an Uber vs leasing or owning a vehicle for the user's main source transportation. I will be using a dataset that consists of six years of Uber ride data to caculate which method would be cheaper for this person, and what the break even cost would be to choose one method over another. In the following project, I highlight my skills of cleaning/standarizing large datasets, as well as my familiarity of python and the use of libraries such as Pandas, Numpy, and MatplotLib. 

#****Data Source**
The following data was found from https://nealmueller.com/uber/, and includes Uber ride data over a six year period. This includes: date of the ride, time of the ride, type of ride/ uber vehicle used, price, start and end time, net travel time, and  milages traveled.

**Steps taken in Project**
1st step: to import and standardize/clean the data.
 -This included dropping unidentifiable ride types, converting the start and end ride times to datetime function,recaculating net travel time,  dealing with              missing values,and handling variations in the spelling/capitalization of data. 

2nd step: look at miles traveled
 - In the 2nd step, I caculated the total miles traveld by uber each year, and displayed my findings using a pivot table. With this information, we can see that the milage traveled per year is less then that of the maximum that could be traveled without additional costs if the user was to lease a vehicle. 

3rd step: caculate yearly cost of uber travel
 - Next, I caculated the total spent on uber travel each year, and displayed the result using a pivot table with the sum function. The results show us the breakeven cost, of what the maximum monthly lease costs or what the maximum spent on a vehicle each month would have to be to break even with taking a uber instead.


4th step:
In the 4th step, I made a dataframe to hold the current costs of leasing a vehicle, and the monthly costs for vehicles that the user already stated he had. These numbers for the bmw and the jeep cherokee came from Neal Muller's website. I will then using the  matplotlib library to highlight these numbers in a graph, and show how they compare to the yearly cost of using Uber.

**Final Steps**
I am continuing to work on this project, and will upload updates as I complete them
