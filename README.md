# Weather-Web-App

**Project Description**

The Weather Web App is a lightweight client-side application that provides real-time weather updates for any city in the world. Users can input a city name to retrieve current weather data such as temperature, humidity, wind speed, and weather conditions. The application uses a third-party Weather API to fetch accurate and up-to-date information. Designed with HTML, CSS, and JavaScript, the app features a clean, responsive UI that works seamlessly across desktops, tablets, and mobile devices.

**Technical Decisions and Overview**

**Frontend**
* Tech Stack: HTML, CSS, JavaScript
* Responsive Design: CSS media queries ensure a mobile-friendly and responsive layout.
* UI/UX: Built an intuitive interface for entering city names and displaying weather information.
* API Integration: Utilized a public weather API (e.g., OpenWeatherMap) to fetch live data based on user input.
* Error Handling: Validates city input and displays user-friendly error messages for invalid entries or API failures.
* Data Display: Renders temperature, humidity, wind speed, and weather conditions dynamically using DOM manipulation.

**Features**
* Global Search: Search for any city worldwide and get instant weather updates.
* Real-Time Data: View up-to-date temperature, humidity, wind speed, and weather conditions.
*  Error Handling: Gracefully handles invalid city names and network errors.
*  Live Update: Instantly fetches new data upon user input without reloading the page.

**Setup Instructions**

**Prerequisites** 
* Modern web browser (e.g., Chrome, Firefox)
* Internet connection (to access the weather API)

**Installation**
* Clone the Repository
  ```bash
  git clone https://github.com/Mehaksinghal2/weather-web-app.git
  cd weather-web-app
  ```

* Open the Application
  * Simply open index.html in your browser:
    ```bash
    open index.html
    ```

* Configure the Weather API
  * Sign up at OpenWeatherMap or another weather API provider.
  * Replace the placeholder API key in the JavaScript file:
    ```bash
    const apiUrl = "https://api.openweathermap.org/data/2.5/weather?&units=metric&q=";
    ```

**Project Structure**
 ```bash
weather-web-app/
│
├── index.html          # Main HTML file
├── styles.css          # Styling using CSS
├── script.js           # JavaScript for logic and API integration
└── README.md           # Project documentation

 ```

**Running the App**
* Open index.html in a web browser.
* Enter any city name into the input field.
* Click the "Search" button to view the weather details.

**Future Enhancements**
* Geolocation: Auto-detect user location to show local weather by default.
* 5-Day Forecast: Add extended weather forecasts.
* Dark Mode: Toggle between light and dark themes.
* Offline Mode: Cache previous results for offline use.
* Map Integration: Display city location using a map API.

**Screen Shot**

<img width="1430" height="746" alt="Image" src="https://github.com/user-attachments/assets/10bb51c8-672e-4f63-9b11-0b28312f3a12" />


