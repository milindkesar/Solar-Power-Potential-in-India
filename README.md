# Solar Power Potential Estimation in India
 

## Objective

We aim to identify the potential regions in India for setting up solar power plants considering several features. Also, we aim to correlate the production of one plant with different seasons and generalize this to identify the ideal production conditions.

 

## Background

The demand for renewable energy is increasing continuously and solar energy plays a major role in this. It is important to analyze the current production capacity and identify the areas requiring development and increase the production as much as possible. 

 

## Potential Applications

Can be used to identify the regions requiring development in India with respect to solar energy production.
Can be used to find the ideal conditions for setting up a solar power plant.

## Understanding the Dataset
we have collected the data for all the solar power plants (in India) listed by the Government of India. This data includes the name of power plants, capacity, location (district and state), latitude, longitude, date of commissioning, average domestic electricity rates in Rs./KWh, per capita electricity consumption in KWh, monthly solar radiation, the monthly plane of the array.

## Method of Data Collection
● The list of all the solar power plants in India has been obtained by scraping the
annual renewable energy plant report which is made available by the
government.
● The average domestic electricity rates of the states for the year 2020 are
collected from the “Bijli Bachao” website.
● Per capita, electricity consumption for the year 2018-19 in KWh is collected from
the press information bureau.
● The latitude and longitude of the district in which the solar plant is located are
collected using Geocoder and using these coordinates the average monthly
Solar Radiation is obtained using the PVWatts Solar API.

