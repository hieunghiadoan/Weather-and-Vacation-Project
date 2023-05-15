## Weather and Vacation Analysis

This project aims to analyze weather data of various cities to understand the relationship between weather variables and the latitude of the cities. We also utilize the analyzed data to plan future vacations by selecting ideal weather conditions for our trip and finding hotels in the cities that meet our criteria.

### Part 1: WeatherPy

In this part, we create a Python script to visualize the weather of over 500 cities of varying distances from the equator using the `citipy` Python library, the OpenWeatherMap API, and our problem-solving skills.

We generate scatter plots to showcase the following relationships:

- Latitude vs. Temperature
- Latitude vs. Humidity
- Latitude vs. Cloudiness
- Latitude vs. Wind Speed

We also compute linear regression for each relationship, separating the plots into Northern Hemisphere (greater than or equal to 0 degrees latitude) and Southern Hemisphere (less than 0 degrees latitude).

### Part 2: VacationPy

In this part, we use our weather data to plan future vacations. We use Jupyter notebooks, the `geopandas` Python library, and the Geoapify API to create map visualizations of our ideal vacation spots.

We narrow down the city_data DataFrame to find our ideal weather conditions and use the Geoapify API to find the first hotel located within 10,000 meters of our coordinates.

### Getting Started

1. Clone the repository to your local machine.
2. Install the required libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `requests`, `citipy`, and `geopandas`.
3. Obtain API keys for [OpenWeatherMap](https://openweathermap.org/api) and [Geoapify](https://www.geoapify.com/).
4. Create an `api_keys.py` file in the project directory and add your API keys as variables.
5. Open the `WeatherPy.ipynb` and `VacationPy.ipynb` Jupyter notebooks to explore the analyses and visualizations.

### Technologies Used

- Python
- Jupyter Notebooks
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Requests
- Citipy
- Geopandas
- OpenWeatherMap API
- Geoapify API

