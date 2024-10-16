# Chicago Taxi Trips Project
## Description
This project aims to analyze taxi usage patterns, spatial distribution, and financial aspects in the city of Chicago over a period of time.
## Chicago Taxi Trips Dataset
This dataset includes taxi trips from 2013 to the present, reported to the City of Chicago in its role as a regulatory agency. To protect privacy but allow for aggregate analyses, the Taxi ID is consistent for any given taxi medallion number but does not show the number, Census Tracts are suppressed in some cases, and times are rounded to the nearest 15 minutes. Due to the data reporting process, not all trips are reported but the City believes that most are.
## Dataset
The dataset used comes from Google Cloud and can be found [here] (https://bigquery.cloud.google.com/dataset/bigquery-public-data:chicago_taxi_trips).
### Key Features
- **Trip ID**: A unique identifier for each trip, facilitating easy tracking and analysis.
- **Taxi I**: An identifier for the taxi involved in each trip, enabling tracking of individual vehicles.
- **Trip Start Timestamp**: When the trip started, rounded to the nearest 15 minutes.
- **Trip End Timestamp** : When the trip ended, rounded to the nearest 15 minutes.
- **Trip Seconds** : Time of the trip in seconds.
- **Trip Miles** : Distance of the trip in miles.
- **Pickup Census Tract** : The Census Tract where the trip began. For privacy, this Census Tract is not shown for some trips. This column often will be blank for locations outside Chicago.
- **Dropoff Census Tract** : The Census Tract where the trip ended. For privacy, this Census Tract is not shown for some trips. This column often will be blank for locations outside Chicago.
- **Pickup Community Area** : The Community Area where the trip began. This column will be blank for locations outside Chicago.
- **Dropoff Community Area** : The Community Area where the trip ended. This column will be blank for locations outside Chicago.
- **Fare** : The fare for the trip.
- **Tips** : The tip for the trip. Cash tips generally will not be recorded.
- **Tolls** : The tolls for the trip.
- **Extras** : Extra charges for the trip.
- **Trip Total**: Total cost of the trip, the total of the previous columns.
- **Payment Type** : Type of payment for the trip.
- **Company** : The taxi company.
- **Pickup Centroid Latitude** : The latitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
- **Pickup Centroid Longitude** : The longitude of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
- **Pickup Centroid Location** : The location of the center of the pickup census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
- **Dropoff Centroid Latitude** : The latitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
- **Dropoff Centroid Longitude** : The longitude of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
- **Dropoff Centroid Location** : The location of the center of the dropoff census tract or the community area if the census tract has been hidden for privacy. This column often will be blank for locations outside Chicago.
