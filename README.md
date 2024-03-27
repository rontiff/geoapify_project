WeatherPy and VacationPy
Overview
WeatherPy and VacationPy are Python scripts designed to visualize weather data for over 500 cities and to plan future vacations based on weather preferences. WeatherPy utilizes the citipy Python library and the OpenWeatherMap API to gather weather data, while VacationPy employs Jupyter notebooks, the geoViews Python library, and the Geoapify API for map visualizations.

Part 1: WeatherPy
In WeatherPy, random geographic coordinates are generated, and the nearest city to each latitude and longitude combination is determined using the citipy library. Then, weather data for each city is retrieved from the OpenWeatherMap API. Finally, the collected data is visualized to create representative models of weather across cities.

Part 2: VacationPy
VacationPy utilizes the weather data obtained in Part 1 to plan future vacations. It employs the Geoapify API and the geoViews Python library to create map visualizations. Users can specify their weather preferences, such as temperature, humidity, cloudiness, and wind speed, to identify ideal vacation destinations.

How to Use
To use WeatherPy and VacationPy:
  Ensure you have Python installed on your system.
  Install the required libraries specified in the project files.
  Run WeatherPy.ipynb to gather weather data for over 100 cities and visualize the weather patterns.
  Run VacationPy.ipynb to plan future vacations based on weather preferences and visualize potential destinations on maps.


Dependencies
  WeatherPy and VacationPy require the following dependencies:
  Python 3.x
  Jupyter Notebook
  citipy
  OpenWeatherMap API
  geoViews
  Geoapify API
  Files Included

The project includes the following files:
  WeatherPy.ipynb: Jupyter notebook for WeatherPy script.
  VacationPy.ipynb: Jupyter notebook for VacationPy script.
  README.md: Readme file providing an overview of the project.
  output folder: for data analysis 
