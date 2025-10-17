# itws2110-websys-lab04
AI generated weather web app

### Prompts
Generate a small web app using only HTML, CSS, and JavaScript that shows a user the current weather and air quality in Troy, NY. This web app must use the OpenWeatherMap Current Weather Data API, as well as the aqicn API from aqicn.org.

Requirements: 
- Current weather must include current temperature in degrees Fahrenheit (note that this is provided in Celsius in the OpenWeatherMap API response), current weather conditions, humidity, and the amount of rain expected in the next hour, if any. This data must be gathered from the OpenWeatherMap Current Weather Data API, for which I have a key that I will use for testing. 
- The current weather as described in the API response must be displayed near the current temperature, and near an icon selected based on the current weather (e.g. a sun for sunny, cloud for cloudy, rain for rainy).
- There must also be a description containing other required data, i.e. what temperature it currently feels like (in Fahrenheit), the current humidity, the amount of rain expected in the next hour and the air quality index (with a parenthetical noting what the air quality index means based on whatever value is displayed).
- Special notes: The amount of rain should be in inches - this is provided in millimeters in the API response. This data point also will not exist in the API response at all if no rain is expected, so check for this and if no rain is expected, do not display predicted rainfall at all.

API calls:
Template API calls are provided. These are what you must build your code around to gather data from the OpenWeatherMap and aqicn APIs

aqicn.org API call: https://api.waqi.info/feed/albany/?token=API_KEY

OpenWeatherMap API call: https://api.openweathermap.org/data/2.5/weather?lat=42.73&lon=-73.68&appid=API_KEY
