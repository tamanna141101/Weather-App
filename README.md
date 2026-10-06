# 🌤️ Weather App

A responsive weather application that provides real-time weather information for a searched city using the **OpenWeather API**.

The application displays current weather conditions along with temperature, humidity, atmospheric pressure, wind speed, weather icons, and forecast information.

## 🌐 Live Demo

**[View Live Weather App](https://weatherapp-gules-tau.vercel.app/)**

## ✨ Features

* 🌍 Search weather by city name
* 🌡️ Display current temperature
* ☁️ Show current weather condition
* 🌤️ Display weather icons
* 💧 Display humidity
* 🌬️ Display wind speed
* 📊 Display atmospheric pressure
* 🕒 Show forecast information with date and time
* 🎞️ Interactive forecast slider using Swiper
* 📱 Responsive and user-friendly interface
* 🏠 Loads weather information for Dhaka by default

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6)**
* **Bootstrap 4**
* **OpenWeather API**
* **Swiper.js**
* **Git & GitHub**
* **Vercel**

## 🔄 How It Works

1. Enter a city name in the search box.
2. Click the **Search** button.
3. JavaScript sends a request to the OpenWeather API.
4. The API returns the weather data.
5. The application updates the page dynamically with the weather information.
6. Forecast data is displayed in an interactive slider.

### Data Flow

```text
User enters city
       ↓
JavaScript fetch()
       ↓
OpenWeather API
       ↓
Weather & Forecast Data
       ↓
DOM Update
       ↓
Weather information displayed
```

## 📁 Project Structure

```text
Weather-App/
│
├── images/
│   └── bg-image.jpg
│
├── index.html
├── style.css
├── script.js
└── README.md
```

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/tamanna141101/Weather-App.git
```

### 2. Navigate to the Project

```bash
cd Weather-App
```

### 3. Run the Application

This is a front-end project, so you can open `index.html` directly in your browser.

For a better development experience, you can use **VS Code Live Server**.

## 🌐 API Integration

This project uses the **OpenWeather API** to retrieve weather information such as:

* Current weather
* Temperature
* Humidity
* Atmospheric pressure
* Wind speed
* Weather condition
* Weather icons
* Forecast information

> **Security Note:** API keys are currently used in the client-side JavaScript. For a production-level application, the API key should be protected using a backend or serverless function and environment variables.

## 📸 Screenshots

<img width="1361" height="522" alt="image" src="https://github.com/user-attachments/assets/25bce034-5ea6-4eef-bc59-e0d306b20bcf" />


## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

* Working with REST APIs
* Using JavaScript `fetch()`
* Handling asynchronous API responses
* Working with JSON data
* DOM manipulation
* Dynamically updating web content
* Integrating third-party libraries
* Creating interactive UI components
* Deploying a web application with Vercel

## 🚀 Future Improvements

* Add loading indicators
* Add proper error messages for invalid cities
* Add current-location weather using the Geolocation API
* Add Celsius/Fahrenheit conversion
* Improve mobile responsiveness
* Add weather-based background changes
* Add a detailed multi-day forecast
* Secure the API key using a backend/serverless function
* Improve accessibility and user experience

## 👩‍💻 Author

**Tamanna Islam**

GitHub: [tamanna141101](https://github.com/tamanna141101)

## ⭐ Project

If you find this project useful, feel free to explore the repository and give it a ⭐.
