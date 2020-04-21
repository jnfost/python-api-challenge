# python-api-challenge
 I chose to use the OpenCall API on OpenWeather because I wanted to pull weather data from the same time of day in each city.
 First I ran citipy to get the city names, then I ran those city names through the Weather API to get the correct latitude and
 longitudes. The latitude and longitude used in citipy were not the actual locations of the cities found. I then used the 
 OneCall API (only accepts lat and lng, not city name) to get the weather data for the next day in each city.
 
 Sorry if that's a bit convoluded, but it made sense in my head.
