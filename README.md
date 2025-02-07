# Weather App - React/Vite project

![Project Status](https://img.shields.io/badge/Project%20Status-Finished-green?style=flat-square)
[![CodeFactor](https://www.codefactor.io/repository/github/lindabgaa/weather-app-v1/badge?style=flat-square)](https://www.codefactor.io/repository/github/lindabgaa/weather-app-v1)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue?style=flat-square)](LICENSE)

This project is a weather application built with **JavaScript**, **React**, and **CSS**. It uses the Vite build tool for fast development. The app enables users to effortlessly search for weather information in any city around the world through a user-friendly interface, providing real-time weather forecasts including temperature, humidity, wind speed, and more. <br>

The data is sourced from the API [WeatherAPI](https://www.weatherapi.com/). <br>

[![Endpoint Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fcitimeteo.netlify.app%2F.netlify%2Ffunctions%2FgetApiStatus&style=for-the-badge)](https://stats.uptimerobot.com/Upe7finkYZ/797784086)

## Features

- Fetches the latest weather information.
- Simple and intuitive design for ease of use.
- Optimized for different screen sizes.
- Weather data fetched from a trusted API source [WeatherAPI](https://www.weatherapi.com/).
- Provides comprehensive information, including temperature, humidity, wind speed, weather conditions, as well as sunrise and sunset times.

## Tech Stack

- JavaScript (ES6+)
- React with Vite build tool
- CSS
- [WeatherAPI](https://www.weatherapi.com/)

## Libraries

- **_PropTypes_**: a library used for type-checking React component props, helping to ensure that components receive the correct data types.
- **_he_**: a library for encoding and decoding HTML entities, used to manage API results that may include special characters or codes in city names, ensuring safe rendering of the content.

## Installation & Setup

1. Clone the repository: `git clone https://github.com/your-username/citimeteo.git`
2. Navigate to the project directory: `cd citimeteo`
3. Install dependencies: `npm install`
4. Install libraries:
   - If you’re using PropTypes for type-checking, install it by running: `npm install prop-types`
   - To handle HTML entity encoding and decoding, install the he library: `npm install he`
5. Sign up on [WeatherAPI](https://www.weatherapi.com/) to get your API key
6. Create a **.env** file in the root of the project and add your API key: `VITE_WEATHER_API_KEY=your_api_key_here`
7. Run the development server: `npm run dev`

## Future Improvements

- Add a 5-day weather forecast.
- Provide autocomplete suggestions for city names.
- Add unit conversion options between Celsius and Fahrenheit.
- Enhance animations and overall UI/UX design.

## Demo

A live demo of the Weather App can be found here [citimeteo.netlify.app](https://citimeteo.netlify.app/).

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
