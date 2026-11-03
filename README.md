<div align="center">

# 🌤️ Weather App

**A clean, lightweight weather app built with HTML, CSS, and vanilla JavaScript. Search any city to see its current temperature, conditions, and humidity.**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)

[About](#about) · [Preview](#preview) · [Features](#features) · [Tech Stack](#tech-stack) · [Getting Started](#getting-started) · [Project Structure](#project-structure) · [Roadmap](#roadmap) · [License](#license) · [Author](#author)

<br />

<!-- Replace SCREENSHOT_NAME.png with your real file inside the image/ folder -->
<img src="image/SCREENSHOT_NAME.png" alt="Weather app showing current temperature, conditions, and humidity for a searched city" width="100%" />

</div>

---

## About

Weather App is a simple front-end project that lets you search for a city and instantly see its current weather. It is built with no frameworks or build tools, which makes it a compact example of fetching data from a weather API and rendering it to the DOM with vanilla JavaScript.

## Preview

<div align="center">
  <!-- Add more screenshots here, e.g. mobile view or different cities -->
  <img src="image/SCREENSHOT_NAME.png" alt="Weather app interface with city search and weather details" width="320" />
</div>

## Features

- **City search** with a search input and magnifier icon
- **Current temperature** in °C
- **Weather condition** description
- **"Feels like" temperature**
- **Humidity** percentage with icon
- **Zero dependencies:** plain HTML, CSS, and JavaScript, with Font Awesome loaded from a CDN for icons

## Tech Stack

| Layer | Technology |
| ----- | ---------- |
| Markup | HTML5 |
| Styling | CSS3 |
| Logic | Vanilla JavaScript (`fetch` API) |
| Icons | Font Awesome 6 |
| Data | <!-- e.g. OpenWeatherMap / WeatherAPI --> Weather API |

## Getting Started

No build step is required.

```bash
# Clone the repository
git clone https://github.com/x-hamza47/weather-app
cd weather-app
```

Open `index.html` in your browser, or serve it locally:

```bash
# Using Python
python -m http.server 8000
```

Then visit `http://localhost:8000`.

### API key

<!-- Keep this section only if main.js needs a key. -->
This app fetches data from a weather API. Open `main.js` and set your own API key:

```js
const API_KEY = "YOUR_API_KEY";
```

> **Note:** Don't commit a real API key to a public repository. Use your own key and keep it out of version control.

## Project Structure

```text
weather-app/
├── image/          # Screenshots and image assets
├── index.html      # Page markup
├── style.css       # Styling
└── main.js         # Fetches and renders weather data
```

## Roadmap

- [x] City search
- [x] Temperature, conditions, and humidity
- [ ] High / low temperature
- [ ] Sunrise and sunset times
- [ ] Wind speed and visibility
- [ ] Geolocation ("use my location")
- [ ] °C / °F toggle
- [ ] Error handling for unknown cities

## License

Copyright (c) 2025 Hamza Aamir. All rights reserved.

## Author

**Hamza Aamir**, Full-Stack Developer

[GitHub](https://github.com/x-hamza47) · [LinkedIn](https://www.linkedin.com/in/hamza-aamir-dev/) · [Portfolio](https://hamzaamir-portfolio.web.app/)
