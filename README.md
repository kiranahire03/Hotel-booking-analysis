# Hotel-booking-analysis

**Abstract:**
           The Hotel industry like any other business opens up socioeconomic opportunities for both owner and customer. It has the function of providing hospitality services to customers. These customers can be travelers, foreigners, businessmen, tourists, visitors, etc. Customers are mostly constrained in trying to get a room to pass the night, as the usual practice is to look for a hotel when you have arrived in the particular location, walk in and find out whether there is a vacant room.
           We were provided with a dataset that states all the information about a customer like Which type customer it is, number of adults and children from which country he/she belongs and so on. My analysis help to understand what type of hotel people mostly preferred, factors that govern the hotel bookings, best time to book a hotel room and so on.

**Keywords : Univariate analysis, Bivariate analysis**

**1.Problem Statement**
      We have given a dataset with the information like Number of Adults, Children and babies, their origin countries, customer type, Average Daily rate, length of stay and so on. The main Objective of my analysis is to provide factors that govern the bookings, help to understand what is the best time to book the hotel room, When there is a surge in price and so on.
 We have given the following information in our dataset: 
•	Hotel:  There are two types of hotels in our dataset viz. City Hotel and Resort Hotel
•	Is cancelled:  This attribute tells us that whether booking is cancelled or not
•	Lead time:  This is the time taken between when a customer makes a reservation and their actual arrival
•	Year:  This is the year in which booking was made
•	Month: This is the month in which booking was made
•	Week:  This is the week in which booking was made
•	Day: This is the day on which booking was made
•	Stays in weekend nights:  Number of nights during weekend stay
•	Stays in week nights:  Number of nights during week stay
•	Adults:  Number of total adults 
•	Children:  Number  of children
•	Babies:  Number of babies
•	Meal:  Type of Meal
•	Country:  Country to which customers belongs
•	Distribution channel:  This is the medium through customer book their room 
•	Repeated Guest: This tells that whether the guest is repeated or not
•	Reserved Room Type:  Room type reserved by customer
•	Assigned Room Type:  Room type assigned to customer
•	Customer Type: This is the type of customer
•	ADR:  This is the average Daily Rate

**2. Introduction**
          This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.
Our dataset has 119390 rows and 32 columns. Our goal here is to do an Exploratory data Analysis which could us to get basic understanding of our dataset, finding outliers, finding correlation between the data, perform Data visualization and finally getting conclusion. 

**3. Steps Involved**

**●	Data Summary**
After loading the dataset we performed this step to understand the data better in the dataset and creating various graphical representations to get some conclusion from it.
This step is an important method for getting a grasp on the meaning of the content of a large collection of data. It basically simplify data for better understanding of our dataset. 


**●	Null values Treatment**
Our dataset contains a large number of null values which might tend to disturb our accuracy hence we dropped them at the beginning of our project in order to get a better result. In our dataset attributes like ‘Agent’ and ‘Company’ have lot of null values so we dropped them from our dataset.


**•	Identify relationships in dataset** 
Correlation analysis measures the statistical relationship between two different variables. Correlation evaluates the direction as well as strength of a relationship between continuous variables. Correlation coefficient can range from -1 to +1, which signifies strong negative to strong positive relation between the variables




**•	Outliers** 
An outlier is a data point that differs significantly from other observations. Outliers are problematic for many statistical analyses because they can cause tests to either miss significant findings or distort real results. In our dataset we have outliers in children, Adult, Number of nights in weekend .

**•	Univariate Analysis**
Univariate analysis is the simplest form of analyzing data. “Uni” means one that means data has only one variable. It doesn't deal with causes or relationships and it's major purpose is to describe; It takes data, summarizes that data and finds patterns in the data.
In our EDA we have following Univariate Analysis
         1.   Top 10 Countries having most number of customers
         2.   Most Customer Type
         3.   Top Distribution channel
         4.   Year with Maximum Customers  

**•	Bivariate Analysis**
Bivariate analysis is one of the simplest forms of quantitative (statistical) analysis. 
It is the analysis of two variables for the purpose of determining the empirical relationship between them. It is the analysis of the relationship between the two variables.
In Bivariate Analysis we have 
                1.   Analysing   cancelled  bookings data
                2.   Find out which type of hotel has most number of customers
                3.   Best time to book the room
                4.   Number of arrivals per year


**•	Conclusion**
After Performing Exploratory Data Analysis we get following insights from the data :
1.	City Hotel had most number of customers than Resort Hotel.
2.	January month has lowest Rate comparing to other months. Hence January is the best time to book the room.
3.	Most number of customer used travel agents to book their room.
4.	Maximum Hotel Bookings are during the year 2016 followed by 2017.
5.	Most number of customers are of Transient Type.
6.	Most number of customers are from Portugal followed by Great Britain and then Spain.
7.	About 50% of all bookings are cancelled.
8.	Highest daily rates occurred in the summer (June, July, August)
