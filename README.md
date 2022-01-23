<!-- Banner -->
![Banner](https://cdn.crello.com/api/media/medium/419542852/stock-photo-cropped-view-businessman-formal-wear)

# Chicago E-Scooters Linear Regression

<!--Introduction -->

This analysis was part of my contribution to a group assignment which aimed to answer the question "Should Sydney adopt an E-scooter program?".

In this project I develop a linear regression model which predicts the volume of escooter trips after considering a number of related variables such as time of day and weather. 

<!-- Data Sources -->
# Data Sources 

The datasets that will be used in this analysis are sourced from the City of Chicago database for relevant traffic surveys, and Iowa State University for weather statistics. The links to the original data sources and brief description are listed below:

* [E-Scooter Trips - 2020](https://data.cityofchicago.org/api/views/3rse-fbp6/rows.csv?accessType=DOWNLOAD)
    * Electric scooter trips taken during the 2020 Chicago pilot program. 
    * _NOTE: file size was too large for repository, data was pulled directly from link_
* [Weather Statistics](https://mesonet.agron.iastate.edu/request/download.phtml?network=IL_ASOS)
    * Weather statistics gathered by Iowa State University
    * Available in the Data folder `MDW.csv`
* [CTA - Ridership - Daily Boarding Totals](https://data.cityofchicago.org/api/views/6iiy-9s97/rows.csv?accessType=DOWNLOAD)
    * This dataset shows systemwide boardings for both bus and rail services provided by CTA
    * Available in the Data folder `CTA_-_Ridership_-_Daily_Boarding_Totals.csv`
* [Taxi Trips](https://data.cityofchicago.org/api/views/wrvz-psew/rows.csv?accessType=DOWNLOAD)
    * Taxi trips reported to the City of Chicago in its role as a regulatory agency. 
    * _NOTE: file size was too large for repository, data was pulled directly from link_
    * Summaries of the data Available in the Data folder under `Taxi_Summary.csv` and `Taxi_Count_Summary.csv`
* [Traffic Crashes - Vehicles](https://data.cityofchicago.org/api/views/68nd-jvt3/rows.csv?accessType=DOWNLOAD)
    * This dataset contains information about vehicles involved in a traffic crash.
    * _NOTE: file size was to large for repository, data was pulled directly from link_
    * Summaries of the data available in the Data folder under `Traffic_Incident_Summary.csv.csv` 
* [Chicago community area population](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6)
    * This dataset contains information about community area population, area and density for Chicago
    * Available in the Data folder `chicago_community_population.csv`
* [Boundaries - Community Areas](https://data.cityofchicago.org/Facilities-Geographic-Boundaries/Boundaries-Community-Areas-current-/cauq-8yn6#Export)
    * Current community area boundaries in Chicago.
    * Available in the Data folder `Boundaries - Community Areas (current).geojson`

The datasets were cleaned and joined to create two data frames from which models could be built.
