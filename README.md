***Project overview and objectives***

The project focuses on predicting a wealth index for regions in Ghana, Kenya, and Nigeria,
transitioning from a regression problem to a binary classification task. The primary objectives
are:

● To explore the dataset and identify key patterns and relationships

● To develop a stacking ensemble for regression to predict the continuous wealth index

● To define a new binary target variable and build a tuned Random Forest classifier,
addressing class imbalance . The analysis employs data preprocessing, ensemble
methods, and classification techniques, providing insights into wealth prediction and
classification challenges within the given timeframe.

Data Description
The file “wealth.csv” contain the dataset and the variables used are :

• Global Human Settlement Layer. Based on data from the GHSL project.

**ghsl_water_surface** : the fraction of land within 5km of the cluster that is classified as water surface

**ghsl_built_pre_1975** : the fraction of land within 5km of the cluster that is classified as built-up before
1975

**ghsl_built_1975_to_1990**, **ghsl_built_1990_to_2000**, **ghsl_built_2000_to_2014** : same
logic for these variables.

**ghsl_not_built_up** : land that was never built up

**ghsl_pop_density** : population density for the surrounding area (5km radius)

• Landcover: based on the Copernicus Global Land Cover Layers

**Landcover_crops_fraction** : the fraction of land within 5km of the cluster that is classified as cropland.

**landcover_urban_fraction** : the fraction of land within 5km of the cluster that is classified as urban.

**Landcover_water_permanent_10km_fraction** : the fraction of land within 10km of the cluster that
is classified as permanent water

**Landcover_water_seasonal_10km_fraction** : the fraction of land within 10km of the cluster that is
classified as seasonal water.

**Nighttime_lights** : a classic indicator of economic activity

**Dist_to_capital** : distance to the countries capital

**Dist_to_shoreline** : distance to the nearest ocean shoreline

**urban_or_rural** : Is the cluster in an urban (‘U’) or rural (‘R’) setting
