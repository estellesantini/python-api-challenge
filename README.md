# python-api-challenge

## Objective:
Apply Python requests, APIs, and JSON traversals to answer the question: "What is the weather like as we approach the equator?"

## Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"

Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

This exercise is broken down into two parts: WeatherPy and VacationPy.

## WeatherPY
In this deliverable, I created a Python script to visualize the weather of over 500 cities of varying distances from the equator. I used the citipy Python libraryLinks to an external site., the OpenWeatherMap APILinks to an external site., and my problem-solving skills to create a representative model of weather across cities.

- Create scatter plots to showcase the relationship between weather variables and latitude.
    - Latitude vs. Temperature
    - Latitude vs. Humidity
    - Latitude vs. Cloudiness
    - Latitude vs. Wind Speed
- Compute linear regression for each of these relationships in the northern and southern hemisphere:
    - Temperature (C) vs. Latitude
    - Humidity (%) vs. Latitude
    - Cloudiness (%) vs. Latitude
    - Wind Speed (m/s) vs. Latitude
- Describe each relationship.

## VacationPy
My main task was to use the Geoapify API and the geoViews Python library and employ my Python skills to create map visualizations and plan future vacations. This is done by doing the following:

- Create a map that displays a point for every city in the city_data_df DataFrame as shown in the following image. The size of the point should be the humidity in each city.
- Narrow down the city_data_df DataFrame to find your ideal weather condition. 
- Create a new DataFrame called hotel_df to store the city, country, coordinates, and humidity.
- For each city, use the Geoapify API to find the first hotel located within 10,000 meters of your coordinates.
- Add the hotel name and the country as additional information in the hover message for each city on the map as in the following image: