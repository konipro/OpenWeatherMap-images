
# OpenWeatherMap-Image API

This "API" converts [weather codes](https://openweathermap.org/weather-conditions) from [OpenWeatherMap](https://openweathermap.org/) into images. This can be helpful if you use OpenWeatherMap and want to show your users suitable images for the current weather situation.

## How to use

Clone the project on your CDN/WebServer. If necessary, in a subfolder. 

Call the path, plus the IconCode and the extension "JPG":
https://yourweatherapi/images/ `WeatherConditionCode` .jpg

Example/Demo: https://cdn.diestadt.app/i/weather/212.jpg

### Code-List

[Weather-Condition-Code-List](https://openweathermap.org/weather-conditions#Weather-Condition-Codes-2) (Use the ID!)


### Sizing

All images are in 1080px X 608px size (16:9 aspect ratio). But you can also load them in double size.

https://yourweatherapi/images/ `WeatherConditionCode`@2x.jpg
## Example Images

heavyThunderstorm [(ID: 212)]((https://openweathermap.org/weather-conditions#Weather-Condition-Codes-2))
![heavyThunderstorm](https://cdn.diestadt.app/i/weather/212@2x.jpg)

haze [(ID: 721)]((https://openweathermap.org/weather-conditions#Weather-Condition-Codes-2))
![haze](https://cdn.diestadt.app/i/weather/721@2x.jpg)

scattered clouds: 25-50% [(ID: 802)]((https://openweathermap.org/weather-conditions#Weather-Condition-Codes-2))
![clouds](https://cdn.diestadt.app/i/weather/802@2x.jpg)

overcast clouds: 85-100% [(ID: 804)]((https://openweathermap.org/weather-conditions#Weather-Condition-Codes-2))
![clouds](https://cdn.diestadt.app/i/weather/804@2x.jpg)

## Sources & Licens 

 - [pexels.com](https://www.pexels.com/)

All photos and videos are free to use. Attribution is not required :)
You can modify the photos – Be creative! 
## Creator

### On GitHub
- [@pexels](https://github.com/pexels) - Images 🇩🇪 (/🇺🇸)
- [@konipro](https://www.github.com/konipro) - Cutting & Research  🇩🇪 (/🇺🇸)

### Help us!
The whole thing is not yet a real API, there are certainly better images, cool functions, but that can still be better! 
So feel free to collaborate. 

Ideas:
- Day and night images
- Videos / GIFs
- An API
- XD file for editing & easy export
