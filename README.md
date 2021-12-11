# World_Weather_Analysis
## Overview of Project
The Weather Database Challenge is to assist a new App called Plan My Trip with changes to that will take take the app to the next level. These are the recommended changes that will be made to the PlanMy Trip App.
* Add the weather description to the weather data 
* Have the beta testers use input statements to filter the data for their weather preferences, which will be used to identify potential travel destinations and nearby hotels. 
* From the list of potential travel destinations, the beta tester will choose four cities to create a travel itinerary. 
* Using the Google Maps Directions API, you will create a travel route between the four cities as well as a marker layer map.

## Retrieve Weather Data 
Retrieve all of the following information from the API call.
* Latitude and longitude
* Maximum temperature
* Percent humidity
* Percent cloudiness
* Wind speed
Weather description (for example, clouds, fog, light rain, clear sky)
Add the weather data to a new DataFrame 
Export the DataFrame as WeatherPy_Database.csv into the Weather_Database folder with the following files in the Weather_Database folder:
* The Weather_Database.ipynb file
* The WeatherPy_Database.csv file
## Customer Travel Destinations Map
Input statements are written to prompt the customer for their minimum and maximum temperature preferences. 
A new DataFrame is created based on the minimum and maximum temperature, and empty rows are dropped. 
The hotel name is retrieved and added to the DataFrame, and the rows that don’t have a hotel name are dropped. 
The DataFrame is exported as a CSV file into the Vacation_Search folder and is saved as WeatherPy_vacation.csv. 
A marker layer map with pop-up markers for the cities in the vacation DataFrame is created, and it is uploaded as a PNG. Each marker has the following information;
* Hotel name
* City
* Country
Current weather description with the maximum temperature
The marker layer map is saved and uploaded to the Vacation_Search folder as WeatherPy_vacation_map.png. 
Vacation_Search folder including;
* The Vacation_Search.ipynb file
* The WeatherPy_vacation.csv file
* The WeatherPy_vacation_map.png image

## Travel Itinerary Map
DataFrames created one for each city on the itinerary. 
The latitude and longitude pairs for each of the four cities are retrieved. 
A directions layer map between the cities and the travel map is created and uploaded as WeatherPy_travel_map.png. 
A DataFrame that contains the four cities on the itinerary is created. 
A marker layer map with a pop-up marker for the cities on the itinerary is created, and it is uploaded as WeatherPy_travel_map_markers.png. Each marker has the * following information: 
* Hotel name
* City
* Country
Current weather description with the maximum temperature with the following in the Vacation_Itinerary folder: 
* The Vacation_Itinerary.ipynb file
* The WeatherPy_travel_map.png image
* The WeatherPy_travel_map_markers.png image
