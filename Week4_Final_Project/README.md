# CourseEra Capstone - Data Analysis Using Python - Final Project
![CourseEra](https://github.com/maindolaamit/Coursera_Capstone/blob/master/Week4_Final_Project/img/coursera-logo-nobg.png)

## New Restaurant Analysis
Restaurant business has seen a great surge after the booming of online services such as recommendation system, Online Order, Home Delivery etc. It’s Sophistication is increasing everyday, exploring new dimensions.

Due to increased business it is paramount to know the existing market for Restaurants in a city. Recommendation to business owners about places perfect for opening a new Restaurant with a particular Cuisine where the owner would get best traffic for the Restaurant. 

I build a Analysis system using Zomato Data for the business owners to analyze the market based on Cuisines, Nightlife, Popularity and Restaurants types. The Insights derived from the analysis is helpful in understanding the existing business and how or which area lacks the service.

## Zomato Analysis:
Zomato API Analysis is one of the most useful analysis for foodies who want to taste the best cuisines of every part of the world which lies in their budget. This analysis is also for those who want to analyze the existing restaurants in various parts of the city for the cuisines, their distribution and traffic which would help them to decide for the best place to open a new Restaurant. :hotsprings:
### For more information on Zomato API and Zomato API key
•	Visit : [https://developers.zomato.com/api](https://developers.zomato.com/api)<br>
•	Data Collection: [https://developers.zomato.com/documentation]( https://developers.zomato.com/documentation)

## Data

### Fetching the data: 
•	City areas has been fetched from mapsofindia [https://www.mapsofindia.com/chandigarh/localities/]
•	Data has been collected from the Zomato API in the form of .json files(raw data) 
•	Raw data can be seen [here](https://github.com/maindolaamit/Coursera_Capstone/Zomato_API_Analysis/Raw_Data)

### Data Collection:
Data collected can be seen as a raw .json file [here](https://github.com/maindolaamit/Coursera_Capstone/tree/master/Week4_Final_Project/raw_data)


### Data Processing :
 Data Processing has been done on the following categories: 
1.	Cuisine
2.	City
3.	Location

The collected data has been stored in the Comma Separated Value file [Zomato.csv](https://github.com/maindolaamit/Coursera_Capstone/Zomato_API_Analysis/csv/zomato.csv). Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:
 
•	**City:** City in which restaurant is located<br>
•	**Area:** Area of the City in which restaurant is located<br>
•	**Area Latitude:** Latitude coordinate of the restaurant's location<br>
•	**Area Longitude:** Longitude coordinate of the restaurant's location<br>
•	**Popularity Index:** Popularity of the area of city<br>
•	**Nightlife Index:** Popularity at night of the area of city<br>
•	**Top Cuisines:** Famous Cuisines of the area of city<br>
•	**Restaurant Id:** Unique id of every restaurant across various cities of the world<br>
•	**Restaurant Name:** Name of the restaurant<br>
•	**Cuisines:** Cuisines offered by the restaurant<br>
•	**Average Cost for two:** Cost for two people in different currencies :couple: <br>
•	**Price range:** range of price of food<br>
•	**Has Online delivery:** yes/ no<br>
•	**Has Table booking:** yes/no<br>
•	**Aggregate Rating:** Average rating out of 5<br>
•	**Rating text:** text on the basis of rating of rating<br>
•	**Votes:** Number of ratings casted by people<br>
•	**Locality:** Location in the city<br>
•	**Address:** Address of the restaurant<br>
•	**Latitude:** Latitude coordinate of the restaurant's location<br>
•	**Longitude:** Longitude coordinate of the restaurant's location<br>
*******************************************************************************************

# Analysis Performed: 

Various analysis have been performed via Visualization on the Data using Matplotlib and Seaborn for the number of Restaurants distribution in areas, Top 10 rated restaurants, Restaurants distribution by cuisines, most popular cuisines in an area etc. 

### Objective:

To perform various kinds of Visualization on the data to know it better.

<img width="1280" alt="Restaurants_count_per_area" src="https://github.com/maindolaamit/Coursera_Capstone/blob/master/Week4_Final_Project/img/Restaurants_count_per_area.png">

<img width="1280" alt="Restaurant_price_range_counts" src="https://github.com/maindolaamit/Coursera_Capstone/blob/master/Week4_Final_Project/img/Restaurant_price_range_counts.png">

### Approach:

Using pandas, grouping 'Restaurant' and 'Cuisines', the aggregate rating is calculated and then the top and least rated restaurants are found for every area in the city.

### Steps: 

1.	The file(zomato_city_restaurants.csv) is read for the input to the data frame.
2.	Performing data wrangling to create Visualization using Seaborn and Matplotlib.
3.	The data is grouped by various parameters and sorted to evaluate multiple Visualization to determine the existing market and factors affecting it.
4.	Use KNN Clustering Algorithm to cluster the Restaurants.
5.	Analysis of the clustered Restaurants.


### Deliverables:

•	CSV files: [Download here]( https://github.com/maindolaamit/Coursera_Capstone/tree/master/Week4_Final_Project/csv)<br>


•	JSON files: [Download here]( https://github.com/maindolaamit/Coursera_Capstone/tree/master/Week4_Final_Project/raw_data)<br>


•	Images: [Download here]( https://github.com/maindolaamit/Coursera_Capstone/tree/master/Week4_Final_Project/img)<br>

### Conclusion: 

:thumbsup: 
From the analysis above (graphs and csv), we can easily determine the various restaurants of the Chandigarh. From Clustering we can see the areas having kind of restaurants.
************************************************************************************************************************************************************************************************
