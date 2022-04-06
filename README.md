# Forecasting-on-time-series-data---agriculture

We are given the monthly production quantity for a certain agricultural product (let’s call it Grople syrup, note - no relation to actual Maple Syrup) in 10 different provinces of a country between January 2015 to December 2020. This Grople syrup comes from a fruit. It takes a few months for the fruits to grow on the trees which bear them. It also takes a few days to extract the syrup from the fruits after they have been harvested.

The goal is to predict the monthly production quantity from January 2021 to December 2021

We have been given 5 .csv files containing pertinent data. Here are the files and their descriptions.

Data:
  
Production Quantity.csv has 4 columns <br />
start_date, end_date   : start day and end day of each month between January
                         2015 to Dec 2020. <br />
prod                   : production quantity of Grople syrup in tonnes at monthly frequency<br />
region_id              : A unique identifier for the 10 provinces <br />



Daily Precipitation.csv has 4 columns<br />
start_date, end_date   : start day and end day at a daily frequency between January 1, 2014 to Mar 13, 2022.<br />
precip                 : Precipitation quantity (in mm) at daily frequency<br />
region_id              : A unique identifier for the 10 provinces<br />

Daily Soil Moisture.csv has 4 columns<br />
start_date, end_date   : start day and end day at a daily frequency between January 1, 2014 to Mar 6, 2022.<br />
smos                   : Soil Moisture at 5cm depth (measured by the ratio Vol/Vol) at daily frequency<br />
region_id              : A unique identifier for the 10 provinces<br />

Daily Temperature.csv has 4 columns<br />
start_date, end_date   : start day and end day at a daily frequency between January 1, 2014 to Mar 6, 2022.<br />
temp                   : Average daily temperature on the surface of the land (in celsius) at daily frequency<br />
region_id              : A unique identifier for the 10 provinces<br />

Eight Day NDVI.csv has 4 columns<br />
start_date, end_date   : start day and end day at a daily frequency between January 1, 2014 to Mar 6, 2022.<br />
ndvi                   : Normalized Difference Vegetation Index (NDVI is a ratio which ranges between [-1, 1] and captures the vegetation abundance of an            area)at 8-day frequency between the given periods.<br />
region_id              : A unique identifier for the 10 provinces<br />

Evaluation Metrics :<br />

R2 Score
