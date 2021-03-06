# # University of Denver Data Analytics Boot Camp: API Homework 

## Background
The first portion of this project consisted of making API calls to OpenWeatherMap and importing that data into Python to create plots showing changes in weather parameters vs the distance from the equator. 
![Equator](Images/API.png)


## Part I - WeatherPy
The first requirement is to create a series of scatter plots to showcase the following relationships:

* Temperature (F) vs. Latitude

 ![heatmap](output_data/Fig1.png)

* Humidity (%) vs. Latitude

 ![heatmap](output_data/Fig2.png)

* Cloudiness (%) vs. Latitude

 ![heatmap](output_data/Fig3.png)

* Wind Speed (mph) vs. Latitude

 ![heatmap](output_data/Fig4.png)

The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude):

* Northern Hemisphere - Temperature (F) vs. Latitude

![heatmap](output_data/Fig5.png)

* Southern Hemisphere - Temperature (F) vs. Latitude

![heatmap](output_data/Fig6.png)

* Northern Hemisphere - Humidity (%) vs. Latitude

![heatmap](output_data/Fig7.png)

* Southern Hemisphere - Humidity (%) vs. Latitude

![heatmap](output_data/Fig8.png)

* Northern Hemisphere - Cloudiness (%) vs. Latitude

![heatmap](output_data/Fig9.png)

* Southern Hemisphere - Cloudiness (%) vs. Latitude

![heatmap](output_data/Fig10.png)

* Northern Hemisphere - Wind Speed (mph) vs. Latitude

![heatmap](output_data/Fig11.png)

* Southern Hemisphere - Wind Speed (mph) vs. Latitude!

![heatmap](output_data/Fig12.png)


### Part II - VacationPy

To complete this part of the assignment,you will need to do the following:

* Create a heat map that displays the humidity for every city from Part I.

  ![heatmap](output_data/humidity_heatmap.png)

* Narrow down the DataFrame to find your ideal weather condition. 

  * A max temperature lower than 80 degrees but higher than 70.

  * Wind speed less than 10 mph.

  * Zero cloudiness
  
  
  ![heatmap](output_data/ideal_weather_df.png)

* Using Google Places API to find the first hotel for each city located within 5000 meters of your coordinates.

* Plot the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

  ![heatmap](output_data/hotel_heatmap.png)


