# 🌦️ Pixel Weather App

A beautiful, retro-styled weather application with pixel art animations that displays current weather conditions, forecasts, air quality, and historical temperature data.

![Pixel Weather App](https://i.imgur.com/0aV2Ajj.png)

## ✨ Features

* **Retro Pixel Art Interface** - Weather conditions visualized with charming pixel animations
* **Real-Time Weather Data** - Current conditions with temperature, humidity, wind, pressure, and visibility
* **5-Day Forecast** - Plan ahead with a 5-day weather outlook
* **Temperature History Chart** - View 24-hour temperature trends with interactive chart
* **Air Quality Index** - Monitor air pollution levels with visual indicators
* **Light/Dark Theme** - Toggle between themes based on your preference
* **Geolocation Support** - Get weather for your current location with one click
* **Unit Conversion** - Switch between Celsius and Fahrenheit
* **Responsive Design** - Works beautifully on desktop, tablet, and mobile
* **Offline Support** - Basic functionality works even without an internet connection
* **Recent Searches** - Quickly access your previously searched locations

## 🚀 Live Demo

Check out the live demo: [Sol Weather App](https://malavikaswapna.github.io/sol/)

## 🔧 Technologies Used

* **HTML5/CSS3** - Semantic markup and modern CSS features
* **JavaScript (ES6+)** - Modern JavaScript with Async/Await for API calls
* **Chart.js** - For temperature history visualization
* **OpenWeatherMap API** - Data source for weather information
* **Service Workers** - For offline capabilities and caching
* **Local Storage** - For saving user preferences and recent searches

## 💻 How to Use

1. **Search for a Location** - Type a city name in the search box and hit Enter
2. **Use Your Location** - Click the "Use My Location" button to get weather for your current position
3. **Toggle Temperature Units** - Switch between Celsius and Fahrenheit with the buttons below the temperature
4. **Change Theme** - Click the "Toggle Theme" button to switch between dark and light themes
5. **View Forecast** - Scroll down to see the 5-day forecast
6. **Explore Historical Data** - Check the temperature chart to see trends over the past 24 hours

# 🧩 Pixel Weather App

## 🛠️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/malavikaswapna/sol.git
cd sol
```
### 2. Get an API key

* Sign up at [OpenWeatherMap](https://openweathermap.org/)
* Go to your account and generate an API key (free tier works great!)

### 3. Add your API key

* Open index.html
* Find this line: ```const apiKey = 'API_KEY'; ```
* Replace ```'API_KEY'``` with your actual API key.

### 4. Run the application
For local development, use a simple HTTP server

```bash
# If you have Python installed:
python -m http.server

# OR with Node.js:
npx http-server

```
### 5. Open in browser

Navigate to whichever port your server is using

## 📱 Progressive Web App Features

This application functions as a Progressive Web App (PWA) with:
* **Offline Support** - Core functionality works without internet
* **Installable** - Can be added to your home screen
* **Responsive** - Adapts to any screen size
* **Fast Loading** - Caches resources for quick startup

## 🌈 Weather Animations

The app includes charming pixel art animations for various weather conditions:
* ☀️ **Clear Sky** - Bright sun (day) or moon and stars (night)
* ☁️ **Clouds** - Fluffy pixel clouds
* 🌧️ **Rain** - Animated raindrops falling from clouds
* ❄️ **Snow** - Gently falling snowflakes
* ⛈️ **Thunderstorm** - Rain with lightning flashes
* 🌫️ **Mist/Fog** - Atmospheric haze effect

## 🧠 Technical Implementation

* **CSS Variables** - For easy theming and maintenance
* **Modular JavaScript** - Clean separation of concerns
* **Error Handling** - Graceful fallbacks for API errors
* **Performance Optimization** - Efficient rendering and network requests
* **Browser Storage** - Persistent storage for preferences and recent searches

## 📝 License

[MIT License](LICENSE)

## 🙏 Acknowledgments

* Weather data provided by [OpenWeatherMap](https://openweathermap.org/)
* Font "Press Start 2P" from [Google Fonts](https://fonts.google.com/)
* Charts powered by [Chart.js](https://www.chartjs.org/)

---

⭐ If you found this project interesting, consider giving it a star!

📧 Questions or suggestions? Open an issue or reach out at malavika.s212@gmail.com
