# Lets go on Vacation!
In the files you find:
 - "WeatherPy.ipynb" - In this notebook we generated a list of cities at random using latitude and longitude.  Then using the Open Weather Database (https://openweathermap.org/) we pull in the associated weather information for each location.
     - This includes cloudiness, humidity, max_temp, and wind speeds
     - With this information we look into the relation some of these conditions may have in relation to the cities latitude and longitude

 - "Output/WeatherCheck.csv" - After we build our list of locations in the "WeatherPy.ipynb" it is saved in a csv to this location.  You can see the total list of locations and weather data here.

 - "VacationPy.ipynb" - In this notebook we took our list of cities and found where certain weather conditions were met.  After we narrowed the list down, we found a list of hotels where available in these locations using the Google Place API (https://developers.google.com/places/web-service/overview).  This gave us a list of great weathered vacation spots to visit!

  - "api_keys.py" - This is where you will enter you api keys for the Open Weather Map and Google Maps.