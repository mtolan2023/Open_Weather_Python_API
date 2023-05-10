# python_api_challenge
Module 6 Challenge

In this repo are 2 projects, titled "WeatherPy" and "VacationPy", both located in the WeatherPy folder.

WeatherPy analyzes weather data from a randomly generated set of cities and uses a series of scatter plots to examine the relationship between latitude and temperature, humidity, cloudiness and windspeed. These plots are exported to the "output_data" folder along with a CSV file of the cities used in the study (which will be used in the VacationPy project. Along with the general scatter plots, the weather data is split into hemispheres and linear regression analysis is performed for each weather trend to determine whether there is a linear relationship between the weather data and latitude. Additional plots and explanations are provided for these.

VacationPy uses the cities.csv generated in WeatherPy to plot the cities on a world map. Plot points increase in size with the humidity measurement for each city. From that dataset, an "ideal" weather condition is described: Between 10-21 degrees Celsius and less than 40% humidity. The dataset is then filtered to include only the cities that fit these criteria and the Geoapify API is used to located a hotel within 10,000 meters of each location. These results are then added to a revised map (City and Hotel Name are included in the hover message for each city. 

The necessary API keys to perform this analysis were added to the .gitignore for this project so that they cannot be exploited. The geographic plots may not display in Github view but they are visible upon download.
