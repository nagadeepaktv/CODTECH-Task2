Name: NAGA DEEPAK T.V

Company: CODTECH IT SOLUTION

ID: CT08DS84

Domain: NOV TO DEC 2024

Mentor: 

Overview of the Project
Project: Weather Forecast App
![image](https://github.com/user-attachments/assets/5dd726a6-dfef-457c-a14e-6a53ed337ef9)
![image](https://github.com/user-attachments/assets/fe431a7b-526b-4417-9d50-29095e9f435d)


Objective
To develop a simple Weather App that provides real-time weather information for a specified city by leveraging the OpenWeatherMap API, allowing users to easily view weather details like temperature, humidity, and wind speed.

Key Activities
1.	User Input for City:
    o	Users can input the name of the city in a text field to retrieve weather information for that location.
2.	Fetch Weather Data:
    o	Upon clicking the "Get Weather" button, the getWeather() function sends an asynchronous request to the OpenWeatherMap API with the city name.
    o	The request includes an API key and specifies the metric unit system (for Celsius temperature).
3.	Display Weather Information:
    o	If the request is successful, the app extracts and displays the following weather data:
    o	City name, weather description, temperature (current and "feels like"), humidity, and wind speed.
    o	If the city is not found or if there’s an error, the app shows an appropriate error message.
4.	Error Handling:
    o	The app handles empty input, invalid city names, and potential network errors, displaying relevant messages to guide the user.

Technologies Used
1.	HTML:
    o	Provides the structure of the app, including the input field, button, and area for displaying weather results.
2.	CSS:
    o	Styles the page with simple, clear formatting to ensure the app is visually appealing and easy to use.
3.	JavaScript:
    o	Uses async/await to handle asynchronous operations for fetching weather data from the API.
    o	Implements DOM manipulation to update the page dynamically with weather details or error messages.
4.	OpenWeatherMap API:
    o	Provides real-time weather data for a given city through the API, including information on temperature, humidity, and wind speed.
