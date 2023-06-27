<div align="center"> 
  <img height="72" width="72" src="./public/logo.svg" alt="App logo" />
</div>

![Landing page screenshot](./public/screenshot.png)

[React Weather](https://react-weather.denniskigen.com) is a beautiful weather app built on top of the [OpenWeatherMap API](https://openweathermap.org/api).

## Getting started

- Sign up over at [openweathermap.org](https://openweathermap.org) and get an API key.
- Fork the project and clone it locally.
- Install dependencies using [pnpm](https://pnpm.io/installation):

  ```sh
  pnpm install
  ```

- Create a file at the root of the project called `.env.local` with the following contents:

  ```
  VITE_API_URL = 'https://api.openweathermap.org/data/2.5'
  VITE_API_KEY = The API key you obtained from openweathermap.org
  VITE_ICON_URL = 'https://openweathermap.org/img/w'
  ```
