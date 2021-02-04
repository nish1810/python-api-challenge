# python-api-challenge

WEATHERPY

This python script visualizes the weather of 500+ cities across the world of varying distance from the equator. To accomplish this,I utilized a Python library, the OpenWeatherMap API, to create a representative model of weather across world cities.
The first requirement is to create a series of scatter plots to showcase the following relationships:
Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude
After each plot, add a sentence or two explaining what the code is analyzing.
The second requirement is to run linear regression on each relationship. This time, separate the plots into Northern Hemisphere (greater than or equal to 0 degrees
latitude) and Southern Hemisphere (less than 0 degrees latitude):
Northern Hemisphere - Temperature (F) vs. Latitude
Southern Hemisphere - Temperature (F) vs. Latitude
Northern Hemisphere - Humidity (%) vs. Latitude
Southern Hemisphere - Humidity (%) vs. Latitude
Northern Hemisphere - Cloudiness (%) vs. Latitude
Southern Hemisphere - Cloudiness (%) vs. Latitude
Northern Hemisphere - Wind Speed (mph) vs. Latitude
Southern Hemisphere - Wind Speed (mph) vs. Latitude

VACATIONPY

This python script creates a heat map that displays the humidity for every city from Weather PY.
I narrowed down the dataFrame to find ideal weather condition destination. For example:
A max temperature lower than 80 degrees but higher than 70, 0 cloudiness and wind speed less than 5 mph. The last part of this scipts searches for hotels within 4 miles of the airport and adds a marker on top of the heat map. 