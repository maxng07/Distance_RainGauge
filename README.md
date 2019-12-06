# Correlation Mapping Using Coordinates </br>
Program to correlate between Weather Forecast Station and Rain Gauge Station in Singapore, based on distance derived from Coordinates (Latitude, Longitude) published using Haversine formulae.

User can input a distance of their choice for comparison in the CLI. The program will then retrieve 2 sets of data from Meterological Service Station in Govtech API end points and perform a calculation between Weather Forecast station and Rain Gauge (measuring near real-time rainfall) Stations based on distance computed using Coordinates. If the distance is within the radius distance specified by the user, the results will be output on stdout /on-screen in JSON format. This can then be copied into a JSON file using a standard text editor. 
For example, a user might want to know within 5km all the Rain Gauge readings from the Weather Forecast station.

The JSON file must be named <b>stations.json </b> to be used together with <a href="https://github.com/maxng07/SG_Weather_GO"> SG_Weather_GO app. </a>

#Usage </br>
-d  defined the distance in Km to be used for comparison. </br>
-h  the help menu of the program </p>

Latest software and release notes <a href="https://github.com/maxng07/Distance_RainGauge/releases"> here </a>

Coordinates (Latitude and Longitude) provided by Meterological Service Singapore from 
<a href="https://data.gov.sg/dataset/weather-forecast"> 2 Hour Weather Forecast </a> and
<a href="https://data.gov.sg/dataset/realtime-weather-readings?resource_id=8bd37e06-cdd7-4ca4-9ad8-5754eb70a33d"> Near Real Time Rainfall </a>
