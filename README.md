# London Bike Sharing Project

## Objectives
**1.** Programatically gather data

**2.** Explore, assess and manipulate the data using the pandas library in Python

**3.** Create impactful visualisations in Tableau

## Objectives
What types of Businesses would find this data useful? 
- Health companies
- Bike Companies:
    - retail (brick and mortar)
    - rental services (lime scooters & bikes) 
## What types of insights would businesses find value? 

## Conclusion
Some of the trends found within the data were as predicted. Cycling activities were significantly lower during rainy days, most likely due to less pleasant and dangerous riding conditions. However seasonal data indicates biking activities were consistent all year round, indicating that raining days were evenly distributed throughout each season.
### Further Analysis Ideas
Conducting further analysis would depend on the clients needs. Consequently what types of Businesses would find this data useful? 
### Health companies
Understanding fitness levels and health needs of the population
- Distances travelled
- Demographic: Age, gender, race
- Qualitative data regardings peoples reasons to not walk or bike to work (driving kids to school on the way to work, feeling unsafe etc.)
### Bike Companies:
#### Retail (brick and mortar) and Rental services (lime scooters & bikes)
Bike companies will find value in data related to targeting the right market
- Biking hotspots in london
- Typical routes 
- Data for other transport methods
    - i.e. trains and cars/ taxis, trying to acquire these users or create transport styles that incorporate some form of passive fitness

## Data source via Kaggle
- [london-bike-sharing-dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)
- Via Uk Govt: [Https://cycling.data.tfl.gov.uk/]

## Metadata
Python dictionaries were made using the following metadata and referenced to make new columns in bike dataset:
- "timestamp" - timestamp field for grouping the data
- "cnt" - the count of a new bike shares
- "t1" - real temperature in C
- "t2" - temperature in C "feels like"
- "hum" - humidity in percentage
- "wind_speed" - wind speed in km/h
- "weather_code" - category of the weather
- "is_holiday" - boolean field - 1 holiday / 0 non holiday
- "is_weekend" - boolean field - 1 if the day is weekend
- "season" - category field meteorological seasons: 0-spring ; 1-summer; 2-fall; 3-winter
- "weathe_code" category description:
1 = Clear ; mostly clear but have some values with haze/fog/patches of fog/ fog in vicinity 2 = scattered clouds / few clouds 3 = Broken clouds 4 = Cloudy 7 = Rain/ light Rain shower/ Light rain 10 = rain with thunderstorm 26 = snowfall 94 = Freezing Fog