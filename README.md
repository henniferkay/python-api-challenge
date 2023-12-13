# python-api-challenge

## Background
The main aim of this project was to make API calls to retrieve information from different platforms. Weather and geospatial data of over 500 cities were obtained, analyzed and plotted on maps.

## Methods
The weather data were requested and retrieved from the OpenWeather API. Temperature, humidity, cloudiness, and wind speed were selected as dependent variables to look at their relationships with latitudes. As expected, hotter temperatures were observed as the latitude decreased. The relationships between different weather conditions and latitudes were graphed as scatter plots, and linear regression was performed on the scatter plots. 

Maps were generated using the Geoapify API and the geoViews Python library. The hotel information was also obtained from the Geoapify API--part of the challenge was to find the cities with preferred weather conditions and locate the first hotel located within 10,000 meters of each city's longitude and latitude.

The analysis and outputs were programmed in Jupyter Notebook--there are two files (WeatherPy.ipynb and VacationPy.ipynb).
