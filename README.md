# COVID-19
Coronavirus disease (COVID-19), an infectious disease which disrupts the respiratory system and causes death in the worst condition. This diseases started to sweep across the globe in early 2020 and causes millions of lives lost especially the elderly group and individuals with underlying health issues. In this project, we attempted to use data visualization tools to:

a) Visualize the progress of this disease across the world, how many lives have been affected. 
b) Visualize the vaccination progress in all countries. 
c) Investigate the correlation between case numbers and other factors collected (vaccination rate, stringency index, population density etc.)

The analysis covers period between 24th February 2020 to 4th December 2021, across 6 continents and 224 locations around the world.

### Data source
The dataset is obtained from the [Our World in Data](https://ourworldindata.org/coronavirus). Our World in Data is a project of the Global Change Data Lab, a non-profit organization based in the United Kingdom.

### Data Information
There are 67 variables and 137830 records in the dataset. The definition of each variables are as follows:

- iso_code: ISO 3166-1 alpha-3 – three-letter country codes

- continent: Continent of the geographical location

- location: Geographical location

- date: Date of observation

- total_cases: Total confirmed cases of COVID-19

- new_cases: New confirmed cases of COVID-19

- new_cases_smoothed: New confirmed cases of COVID-19 (7-day smoothed)

- total_deaths: Total deaths attributed to COVID-19

- new_deaths: New deaths attributed to COVID-19

- new_deaths_smoothed: New deaths attributed to COVID-19 (7-day smoothed)

- total_cases_per_million: Total confirmed cases of COVID-19 per 1,000,000 people

- new_cases_per_million: New confirmed cases of COVID-19 per 1,000,000 people

- new_cases_smoothed_per_million: New confirmed cases of COVID-19 (7-day smoothed) per 1,000,000 people

- total_deaths_per_million: Total deaths attributed to COVID-19 per 1,000,000 people

- new_deaths_per_million: New deaths attributed to COVID-19 per 1,000,000 people

- new_deaths_smoothed_per_million: New deaths attributed to COVID-19 (7-day smoothed) per 1,000,000 people

- reproduction_rate: Real-time estimate of the effective reproduction rate (R) of COVID-19

- icu_patients: Number of COVID-19 patients in intensive care units (ICUs) on a given day

- icu_patients_per_million: Number of COVID-19 patients in intensive care units (ICUs) on a given day per 1,000,000 people

- hosp_patients: Number of COVID-19 patients in hospital on a given day

- hosp_patients_per_million: Number of COVID-19 patients in hospital on a given day per 1,000,000 people

- weekly_icu_admissions: Number of COVID-19 patients newly admitted to intensive care units (ICUs) in a given week

- weekly_icu_admissions_per_million: Number of COVID-19 patients newly admitted to intensive care units (ICUs) in a given week per 1,000,000 people

- weekly_hosp_admissions: Number of COVID-19 patients newly admitted to hospitals in a given week

- weekly_hosp_admissions_per_million: Number of COVID-19 patients newly admitted to hospitals in a given week per 1,000,000 people

- new_tests: New tests for COVID-19 (only calculated for consecutive days)

- total_tests: Total tests for COVID-19

- total_tests_per_thousand: Total tests for COVID-19 per 1,000 people

- new_tests_per_thousand: New tests for COVID-19 per 1,000 people

- new_tests_smoothed: New tests for COVID-19 (7-day smoothed). For countries that don't report testing data on a daily basis, we assume that testing changed equally on a daily basis over any periods in which no data was reported. This produces a complete series of daily figures, which is then averaged over a rolling 7-day window

- new_tests_smoothed_per_thousand: New tests for COVID-19 (7-day smoothed) per 1,000 people

- positive_rate: The share of COVID-19 tests that are positive, given as a rolling 7-day average (this is the inverse of tests_per_case)

- tests_per_case: Tests conducted per new confirmed case of COVID-19, given as a rolling 7-day average (this is the inverse of positive_rate)

- tests_units: Units used by the location to report its testing data

- total_vaccinations: Total number of COVID-19 vaccination doses administered

- people_vaccinated: Total number of people who received at least one vaccine dose

- people_fully_vaccinated: Total number of people who received all doses prescribed by the vaccination protocol

- total_boosters: Total number of COVID-19 vaccination booster doses administered (doses administered beyond the number prescribed by the vaccination protocol)

- new_vaccinations: New COVID-19 vaccination doses administered (only calculated for consecutive days)

- new_vaccinations_smoothed: New COVID-19 vaccination doses administered (7-day smoothed). For countries that don't report vaccination data on a daily basis, we assume that vaccination changed equally on a daily basis over any periods in which no data was reported. This produces a complete series of daily figures, which is then averaged over a rolling 7-day window

- total_vaccinations_per_hundred: Total number of COVID-19 vaccination doses administered per 100 people in the total population

- people_vaccinated_per_hundred: Total number of people who received at least one vaccine dose per 100 people in the total population

- people_fully_vaccinated_per_hundred: Total number of people who received all doses prescribed by the vaccination protocol per 100 people in the total population

- total_boosters_per_hundred: Total number of COVID-19 vaccination booster doses administered per 100 people in the total population

- new_vaccinations_smoothed_per_million: New COVID-19 vaccination doses administered (7-day smoothed) per 1,000,000 people in the total population

- new_people_vaccinated_smoothed: Daily number of people receiving their first vaccine dose (7-day smoothed)

- new_people_vaccinated_smoothed_per_hundred: Daily number of people receiving their first vaccine dose (7-day smoothed) per 100 people in the total population

- stringency_index: Government Response Stringency Index: composite measure based on 9 response indicators including school closures, workplace closures, and travel bans, rescaled to a value from 0 to 100 (100 = strictest response)

- population: Population (latest available values). See https://github.com/owid/covid-19-data/blob/master/scripts/input/un/population_latest.csv for full list of sources

- population_density: Number of people divided by land area, measured in square kilometers, most recent year available

- median_age: Median age of the population, UN projection for 2020

- aged_65_older: Share of the population that is 65 years and older, most recent year available

- aged_70_older: Share of the population that is 70 years and older in 2015

- gdp_per_capita: Gross domestic product at purchasing power parity (constant 2011 international dollars), most recent year available

- extreme_poverty: Share of the population living in extreme poverty, most recent year available since 2010

- cardiovasc_death_rate: Death rate from cardiovascular disease in 2017 (annual number of deaths per 100,000 people)

- diabetes_prevalence: Diabetes prevalence (% of population aged 20 to 79) in 2017

- female_smokers: Share of women who smoke, most recent year available

- male_smokers: Share of men who smoke, most recent year available

- handwashing_facilities: Share of the population with basic handwashing facilities on premises, most recent year available

- hospital_beds_per_thousand: Hospital beds per 1,000 people, most recent year available since 2010

- life_expectancy: Life expectancy at birth in 2019

- human_development_index: A composite index measuring average achievement in three basic dimensions of human development—a long and healthy life, knowledge and a decent standard of living. Values for 2019, imported from http://hdr.undp.org/en/indicators/137506

- excess_mortality_cumulative_absolute: Cumulative difference between the reported number of deaths since 1 January 2020 and the projected number of deaths for the same period based on previous years. For more information, see https://github.com/owid/covid-19-data/tree/master/public/data/excess_mortality

- excess_mortality_cumulative: Percentage difference between the cumulative number of deaths since 1 January 2020 and the cumulative projected deaths for the same period based on previous years. For more information, see https://github.com/owid/covid-19-data/tree/master/public/data/excess_mortality

- excess_mortality: Percentage difference between the reported number of weekly or monthly deaths in 2020–2021 and the projected number of deaths for the same period based on previous years. For more information, see https://github.com/owid/covid-19-data/tree/master/public/data/excess_mortality

- excess_mortality_cumulative_per_million: Cumulative difference between the reported number of deaths since 1 January 2020 and the projected number of deaths for the same period based on previous years, per million people. For more information, see https://github.com/owid/covid-19-data/tree/master/public/data/excess_mortality

### Tool and library
Pandas, Numpy, Seaborn, Matplotlib and Plotly 

### Findings
To date (Dec 2021), due to the recent Omicron variant, there is an ongoing spike in case numbers across the globe especially in North America which marks the continent with the highest case numbers, and United States has the highest case numbers. 
There are many factors cotributing to the increase of case numbers in each country including median age, human development index(A composite index measuring average achievement in three basic dimensions of human development—a long and healthy life, knowledge and a decent standard of living), total deaths, vaccination count, number of smokers, and booster count.


