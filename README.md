# Weather App with GetX

A modern weather application built with Flutter and GetX state management. This app provides real-time weather information with a beautiful user interface that supports both light and dark themes.

## Features

- Real-time weather data using OpenWeather API
- Dynamic theme switching (Light/Dark mode)
- Clean and intuitive user interface
- Location-based weather information using Geolocator
- State management with GetX
- Responsive design for various screen sizes

## Technologies Used

- **Flutter**: Cross-platform UI framework
- **GetX**: State management, routing, and dependency injection
- **VelocityX**: UI utilities and styling
- **HTTP**: API integration
- **Geolocator**: Location services
- **OpenWeather API**: Weather data provider

## Screenshots

### Dark Mode
![App UI Dark](https://github.com/zillur07/Weather-App-with-GetX/assets/87537602/a10de028-b1b7-4fb9-925e-bd93a9726de0)

### Light Mode
![App UI Light](https://github.com/zillur07/Weather-App-with-GetX/assets/87537602/53d61474-c069-41dc-9f5a-12ea1ff21b3a)

## Project Structure

The project follows a clean architecture pattern with GetX:
- `lib/`
  - `controllers/`: GetX controllers for state management
  - `models/`: Data models
  - `views/`: UI screens and widgets
  - `services/`: API and location services
  - `utils/`: Helper functions and constants

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/zillur07/Weather-App-with-GetX.git
```

2. Install dependencies
```bash
flutter pub get
```

3. Add your OpenWeather API key in the configuration file

4. Run the app
```bash
flutter run
```

## Dependencies

- flutter_sdk: ">=2.19.6 <3.0.0"
- get: State management
- velocity_x: UI utilities
- http: API calls
- geolocator: Location services

## Developer

Created by Zillur Rahman

## License

This project is open source and available under the MIT License.

---

Feel free to contribute to this project by creating issues or submitting pull requests.
