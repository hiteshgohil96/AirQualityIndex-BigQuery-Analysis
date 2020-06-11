# AirQualityIndex-BigQuery-Analysis

In this notebook data is extracted from BigQuery Public Data assesible exclusively only in Kaggle. The BigQurey Helper Object will convert data in cloud storage into Pandas DataFrame object. The query syntax is same as SQL. As size of data is very high convert entire data to DataFrame is cumbersome. So query is written such that will be readly available for Visualization.
BigQuery is a RESTful web service that enables interactive analysis of massively large datasets working in conjunction with Google Storage. It is an Infrastructure as a Service that may be used complementarily with MapReduce.

Here, I will be analyzing OpenAQ dataset, which has some information about the air pollutants.

Measurement units a. ug/m3 : micro gram/cubic meter b. ppm : Parts Per Million

Pollutants a. O3 : Ozone gas b. SO2 : Sulphur Dioxed c. NO2 : Nitrogen Dioxed d. PM2.5 : Particles with an aerodynamic diameter less than 2.5μm e. PM10 : Particles with an aerodynamic diameter less than 10μm f. CO : Carbon monoxide

## Goal
The goal of this notebook is to tell a story of the air quality till the year 2019 and in 2020. We all know that 2020 has not started well but due to lockdown in many countries, how the pandemic has played a role in the air quality.

Questions I want to address are:
1.) What was the average AQI before and in 2020 in each country?
2.) What was the highest occuring pollutant in top 5 country before and in 2020?
3.) Correlation between country and pollutants?
4.) Which month has the most AQI overall?

