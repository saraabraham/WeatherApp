# Weather App (Flask)

This is a simple web application built with Python and Flask that allows users to check the current temperature of any city by entering its name.

## Overview

The application utilizes the OpenWeatherMap API to fetch real-time weather data. Users can input a city name through a web form, and the application will display the current temperature and weather conditions for that city.

## Features

* **City Input:** Users can enter the name of any city to get its weather information.
* **Temperature Display:** The application shows the current temperature of the entered city.
* **Weather Description:** Displays a brief description of the current weather conditions (e.g., "Clear sky," "Rain," "Cloudy").
* **"Feels Like" Temperature:** Displays the "feels like" temperature.
* **Simple and User-Friendly Interface:** Easy-to-use web interface.

## Technologies Used

* Python 3
* Flask (web framework)
* Requests (for making HTTP requests to the OpenWeatherMap API)
* python-dotenv (for managing environment variables)
* OpenWeatherMap API

## Prerequisites

* Python 3 installed on your system.
* An OpenWeatherMap API key (sign up at [openweathermap.org](https://openweathermap.org/)).

## Setup and Installation

1.  **Clone the repository:**

    ```bash
    git https://github.com/saraabraham/WeatherApp.git
    ```

2.  **Create a virtual environment (recommended):**

    ```bash
    python3 -m venv .venv
    source .venv/bin/activate  # On macOS/Linux
    .\.venv\Scripts\activate  # On Windows
    ```

3.  **Install dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

4.  **Create a `.env` file:**

    Create a `.env` file in the root directory of the project and add your OpenWeatherMap API key:

    ```
    OPENWEATHER_API_KEY=your_api_key_here
    ```

5.  **Run the application:**

    ```bash
    python3 server.py
    ```

6.  **Open your browser:**

    Open your web browser and go to `http://127.0.0.1:5000/` to access the application.

## Usage

1.  Enter the name of the city in the input field.
2.  Click the "Submit" button.
3.  The application will display the current temperature and weather conditions for the entered city.

