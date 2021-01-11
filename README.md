# MWNB-police-killings
This repository contains data compiled for the Mountain West News Bureau's reporting project on people killed in encounters with the police.

### Data sources
We compiled data from four different independent organizations who collect data on people in the U.S. killed by police:
* [Fatal Encounters](https://fatalencounters.org/)
* [Mapping Police Violence](https://mappingpoliceviolence.org/)
* [Washington Post](https://www.washingtonpost.com/graphics/investigations/police-shootings-database/)
* [The Guardian](https://www.theguardian.com/us-news/ng-interactive/2015/jun/01/the-counted-police-killings-us-database)

These files also include population information, which is from the [U.S. Census Bureau](https://www.census.gov/en.html).

### What is included in this respository
This respository includes files that have aggregated police killings by different geographic regions (entire U.S., states, Census divisions) and by year from the four data sources listed above, as well as the Fatal Encounters database with vehicle-related incidents removed.

### Data dictionary
The fields included in each file are slighty different because they have different geographic levels, but all files include:
* year
* geography (state, postal code, division)
* count-fatalities -- The number of people killed by police in a given geographic region in a given year
* source -- Which of the data sources above it came from: FE = Fatal Encounters; FE_NV = Fatal Encounters with vehicle incidents removed; WaPo = Washington Post; MPV = Mapping Police Violence; Guardian = The Guardian.
* population -- The resident population for the given geography in a given year.
* per-capita -- The number of police killings per population.
* per-million -- The number of police killings per million people.

### For more information
Contact info
