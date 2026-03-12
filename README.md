# Weather in Calendar

It's a simple PHP script generating a .ical formated calendar with a 16 days weather forecast with data from [OpenWeatherMap](https://openweathermap.org/).

## URL parameters

### Usage
You can upload it to your host and enter the following url like so:

```url
https://yourdomain.com/weather-cal.php?city=Luxembourg&units=metric
```

### Options

Key | Values
--- | ------
`city` | `city name` or <br>`city name,state code` or <br>`city name,state code,country code`
`units` | `metric` or `imperial`
`temperature` | `day` or `low-high`
`location` | `show` or `hide`

## System Requirements

- A calendar application that supports .ical
- A system the supports Unicode 7+ *(Released: 2014 June 16)*

## Look

*These are the emojis used so far:*

### Emojis in Event Title

Your Browser | Emoji code | API names
------------ | ---------- | ---------
☀️ | `:sunny:` | `01d`
✨ | `:sparkles:` | `01n`
🌤 | `:sun_behind_small_cloud:` | `02d`, ```02n```
☁️ | `:cloud:` | `03d`, `03n`, `04d`, `04n`
🌧 | `:cloud_with_rain:` | `09d`, `09n`
🌦 | `:sun_behind_rain_cloud:` | `10d`, `10n`
⛈ | `:cloud_with_lightning_and_rain:` | `11d`, `11n`
🌨 | `:cloud_with_snow:` | `13d`, `13n`
🌫 | `:fog:` | `50d`, `50n`
🤔 | `:thinking:` | No match

### Emojis in the Description

Your Browser | Emoji code
------------ | ----------
🌅 | `:sunrise:`
⚡️ | `:zap:`
💧 | `:droplet:`
💨 | `:dash:`
🚩 | `:triangular_flag_on_post:`
