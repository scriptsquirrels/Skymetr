Overview
Skymetr is a Python-based weather application that provides real-time weather data for a specified location using the OpenWeatherMap API. The app displays key weather information, such as current temperature, minimum and maximum temperatures, "feels like" temperature, and humidity, through a graphical interface built with Tkinter.

Features
Real-Time Weather Data: Fetches and displays the current weather, including temperature, min/max temperatures, and humidity.
Graphical User Interface: Designed using Tkinter for a user-friendly experience.
Visual Elements: Includes icons (e.g., a sun icon for clear weather) to enhance the interface.

Technologies Used
Python
Tkinter: For building the graphical user interface.
PIL (Pillow): For handling images within the Tkinter framework.
OpenWeatherMap API: To fetch real-time weather data.

Setup Instructions
Prerequisites
Python 3.x installed on your machine.
An API key from OpenWeatherMap. You can obtain it by signing up for a free account at OpenWeatherMap.
The following Python packages: requests, tkinter, PIL (Pillow).

Installation
1. Clone the Repository: git clone https://github.com/yourusername/skymetr.git
2. Navigate to the Project Directory: cd skymetr
3. Install Required Packages: pip install requests pillow
4. Set Up Environment Variables:
  Create an environment variable WEATHERAPI in your system or set it directly in your script, and assign it your OpenWeatherMap API key.
   On Linux/macOS: export WEATHERAPI='your_openweather_api_key'
   On Windows: set WEATHERAPI='your_openweather_api_key'
   Or, directly in the script: API_KEY = "your_openweather_api_key"
5. Run the Application: phyton skymetr.py

Usage
Once the application is running, it will display the current weather data for the specified latitude and longitude, which is currently set to Chicago, IL (Latitude: 41.878113, Longitude: -87.629799). You can modify the LAT and LONG variables in the script to change the location.

Customization
Change Location: Update the LAT and LONG variables in the script to grab the weather data for a different location.
Update Icons: Replace sun.png with any other weather-related icon to customize the interface.

Contributing
If you'd like to contribute to Skymetr, please fork the repository and submit a pull request. We welcome all improvements, from bug fixes to new features!

License
This project is licensed under the MIT License. See the LICENSE file for more details.
    
