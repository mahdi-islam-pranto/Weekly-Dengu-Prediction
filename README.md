# Weekly Dengue Patient Prediction 

In this analysis we used a series of features collected from two cities and the features relate to environmental factors which helped to predict the number of weekly dengue cases.

## Feature explanation:

NDVI (Normalized Difference Vegetation Index): NDVI values are indicators of vegetation health and can give insights into the environment. Different regions might have varying levels of vegetation, which can affect mosquito breeding habitats and thus dengue spread.

Precipitation Amount: The amount of rainfall during the week. Rainfall can lead to stagnant water, providing breeding grounds for dengue-carrying mosquitoes.

Reanalysis Air Temperature: This indicates the air temperature at different times of the day. Temperature can affect mosquito breeding and virus replication rates.

Reanalysis Dew Point Temperature: The temperature at which air becomes saturated with moisture. This is linked to humidity and can influence mosquito activity.

Reanalysis Precipitation Amount: Similar to "Precipitation Amount," this can give insights into the amount of rainfall.

Reanalysis Relative Humidity: This is the amount of moisture in the air relative to its capacity. High humidity can be favorable for mosquito breeding.

Reanalysis Specific Humidity: The amount of water vapor present in the air. It is related to temperature and can affect mosquito activity.

Reanalysis TDTR (Temperature Diurnal Range): The difference between the maximum and minimum temperatures in a day. It can influence mosquito behavior and virus replication.

Station Temperature: The temperature observed at a specific station. This can provide a localized view of the temperature impact on dengue cases.

Station Diurnal Temperature Range: The temperature range within a day at a specific station.

Station Precipitation: The amount of precipitation at a specific station.

Reanalysis Precipitation Amount (kg/m2): This feature represents the amount of precipitation in kilograms per square meter. It quantifies the total rainfall, which can impact mosquito breeding and the overall environment conducive to dengue transmission.

Reanalysis Saturation Precipitation Amount (mm): This refers to the amount of precipitation as measured by saturation. It's another representation of rainfall, which can contribute to mosquito breeding habitats.

Reanalysis Specific Humidity (g/kg): Specific humidity measures the actual water vapor content in the air per kilogram of air. It's a crucial parameter to assess atmospheric moisture and its influence on dengue transmission.
All the features are categorical except for two cities. We separate the data into two subsets for the two cities San Juan and Iquitos. 

## Models Used

Linear Regression

KNN model

Decision Tree
