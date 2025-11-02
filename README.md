# WeatherWise
WeatherWise is a Python-based weather forecasting application that provides real-time weather updates for any city. It fetches data from the OpenWeatherMap API and displays temperature, humidity, and wind speed in a simple interface. Built using Python and libraries like requests and tkinter, the app is lightweight and easy to use. Just enter a city name to instantly view accurate weather information.
# WeatherWise - Smart Weather Advisor

## Features
- Fetches live weather data for any city.
- Gives actionable advice based on temperature and condition.
- Sends email alerts for extreme weather.
- GUI interface with Tkinter for easy use.

## Setup
1. Install Python 3.10+.
2. Install requests: pip install requests
3. Replace YOUR_OPENWEATHERMAP_API_KEY and email credentials in core/alert.py and core/fetch_weather.py
4. Run GUI: python main.py

## Notes
- Email alerts require a dedicated Gmail + App Password.
- CLI mode is optional and can be activated by commenting out run_gui().
