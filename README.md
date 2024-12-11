# WeatherySky

WeatherySky is a simple weather checker application where users can get the current weather details of any city around the globe. This project is built using **HTML**, **CSS**, and **JavaScript** and utilizes the [OpenWeatherMap API](https://openweathermap.org/api) for fetching real-time weather data.

## Features

- **Check Weather by City**: Enter the name of any city to get its current:
  - Temperature (in Celsius)
  - Humidity (in percentage)
  - Wind Speed (in km/h)

- **Error Handling**: If the entered city name is invalid, the application displays an error message to notify the user.

- **Dynamic Interface**: A sleek and minimalistic UI that changes dynamically based on user inputs.

## Screenshots

### Valid City Input
![Valid City](./Screenshot%202024-12-11%20150953.png)

### Invalid City Input
![Invalid City](./Screenshot%202024-12-11%20150923.png)

## How It Works

1. The user enters the name of a city into the input field and presses the search icon.
2. A request is sent to the OpenWeatherMap API to fetch the weather details of the entered city.
3. If the city name is valid, the weather details are displayed:
   - Temperature
   - Humidity
   - Wind Speed
4. If the city name is invalid, an error message is displayed, prompting the user to try again.

## Technologies Used

- **HTML**: Structuring the webpage content.
- **CSS**: Styling the user interface for an engaging experience.
- **JavaScript**: Adding dynamic functionality to the application.
- **OpenWeatherMap API**: For fetching live weather data.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/WeatherySky.git
   ```
2. Navigate to the project directory:
   ```bash
   cd WeatherySky
   ```
3. Open the `index.html` file in your web browser to run the application.

## API Integration

This project uses the OpenWeatherMap API to fetch weather data. To set up your API key:

1. Sign up at [OpenWeatherMap](https://openweathermap.org/) and get your API key.
2. Replace the placeholder in the JavaScript file with your API key:
   ```javascript
   const apiKey = 'YOUR_API_KEY';
   ```

## Credits

This project was created with love and learning by [Kartikeya Srivastava](https://www.linkedin.com/in/kartikeya-srivastava/).

## Contact

Feel free to reach out:

- **LinkedIn**: [Kartikeya Srivastava](https://www.linkedin.com/in/kartikeya20/)
- **Email**: [kartikeyasrivastava@example.com](mailto:kartik.srvt@gmail.com)

---

"Weather changes, so can you! But for now, you can check the weather!"


