# 🌤️ Weather-App

A clean, responsive weather application built using **HTML**, **CSS**, and **JavaScript**. It fetches real-time weather data based on the city name input and displays the current weather, humidity, wind speed, and a 5-day forecast. The app also handles errors gracefully when an invalid city is entered.

---


## 🚀 Features

- 🔍 Search for any city’s weather
- 🌦️ Displays:
  - Current temperature
  - Weather description
  - Humidity level
  - Wind speed
- 📅 5-day weather forecast
- ❌ 404 error message for invalid city names
- 💻 Responsive and sleek UI with modern design

---

## 🛠️ Tech Stack

- **HTML5** – Markup
- **CSS3** – Styling and layout
- **JavaScript** – Fetching data and dynamic updates
- **OpenWeatherMap API** – For weather data

---

## ⚙️ How It Works

1. User enters the city name in the input box and clicks the search icon.
2. A JavaScript function fetches weather data using the [OpenWeatherMap API](https://openweathermap.org/).
3. If a valid city is found:
   - Displays weather details and forecast.
4. If not:
   - A 404 error message is shown with a styled illustration.

---

## 🔧 Setup Instructions

1. **Clone the repository**

2. **Open index.html in your browser**

3. **Ensure internet access so the app can fetch live weather data.**   

## 🔐 API Key

**If you're using your own OpenWeatherMap API key, replace the key in script.js**:
   const apiKey = "YOUR_API_KEY";
