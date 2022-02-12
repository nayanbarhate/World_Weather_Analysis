# World_Weather_Analysis
## Project Overview
PlanMyTrip is a top travel technology company specialized in internet related services in the hotel and lodging industry.\
This project will enhance the user interface  and functionalities of the PlanMyTrip app with the following steps: 
1. retrieve weather data including the weather description for over 500 cities across the world,
2. create a customer travel destinations map,
3. create a travel itinerary map.

## Results

### Retrieve weather data
The app uses the NumPy dependency to generate 2,000 sets of coordinates (latitude and longitude).\
The Python's [citipy](https://github.com/nayanbarhate/citipy) module is then called to identify the nearest city for each coordinate combination.\
The weather data is retrieved for all identified cities through a request to the [OpenWeatherMap API](https://openweathermap.org/current).

### Create a customer travel destinations map
With Jupyter's gmaps plugin, user's weather preference inputs and requests to the [Google Maps and Places API](https://developers.google.com/places/web-service/search), the app generates a customer travel destinations map.


### Create a travel itinerary map
Using [Google Maps Directions API](https://developers.google.com/maps/documentation/directions/overview) the app generates a travel route between 4 cities selected by the user.
