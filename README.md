# World Weather Analysis

### Project Overview
Analyze, create visuals, and statistically graph the weather data for a potential travel company. Their app PlanMyTrip will use the data to recommend ideal hotels based on clients’ weather preferences. 

### Resources
- Data source: API from OpenWeatherMap, API from GoogleMaps
- Software: Python 3.6.9, Jupyter Notebook, Pandas Library, MatPLotLib, SciPy Libraries

### Objectives
- Provide real-time suggestions for our client’s ideal hotels
- Create a Pandas DataFrame with 500 or more of the world’s unique cities and their weather data in real time. This process will entail collecting, analyzing, and visualizing the data.

## Challenge

### Part 1: Get Weather Description and Amount of Precipitation for Each City
How many cities have recorded rainfall or snow at the time the API was pulled?
- 64 cites have experienced rainfall in the last 3 hours.
- 30 cities have experienced snowfall in the last 3 hours.

### Part 2: Have Customers Narrow Their Travel Searches Based on Temperature and Precipitation
The client chose a location with a minimum temperature of 65 F and maximum temperature of 90 F, and where it has not been raining or snowing in the last 3 hours. 

A map marking the location that meet the clients preferred criteria:
![WeatherPy_vacation_map](https://github.com/hillarykrumbholz/World_Weather_Analysis/blob/master/images/WeatherPy_vacation_map.png)

### Part 3: Create a Travel Itinerary with a Corresponding Map
The client decided to travel somewhere in South America, between Guatemala, Honduras, Belize, and El Salvador.
A map (travel itinerary) is created that shows the route between five cities from the customer’s possible travel destinations in South America. Additionally, a map is created with pop-up markers for the five cities

A map displaying the routes between the five cities they are interested in visiting:
![WeatherPy_travel_map](https://github.com/hillarykrumbholz/World_Weather_Analysis/blob/master/images/WeatherPy_travel_map.png)

A map displaying the pop-up markers for some of the cites in the vacation itinerary:
![WeatherPy_travel_map_markers]
(https://github.com/hillarykrumbholz/World_Weather_Analysis/blob/master/images/WeatherPy_travel_map_markers.png)
