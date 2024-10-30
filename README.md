# MixedModels-Demographics-DeathRate2004

## Overview
Human Demographic Contributions to the 2004 Death Rate by U.S. State and County modeled with a Random Intercept Mixed Model

## Project Description
Based on previous knowledge and the available data, this analysis focused on exploring which human demographic contributed to the death rate by county and state in the U.S. in 2004

# Data
The dataset was sourced from the United States Census Bureau’s 2008 Statistical Abstract of the United States (3). The Census Bureau compiled this data from the CDC’s National Center of Health Statistics, which records mortality and physician data based on complete vital records filed in the registration offices of all states, independent cities, and the District of Columbia. Deaths of nonresident aliens in the United States and U.S. citizens outside the United States have been excluded from the data. Researchers used a multistage probability sample of 36−40,000 households (449 effective primary sampling units) to obtain the demographic data. The variables of primary interest for this analysis are per capita income and number of physicians per 100,000 people, and their influence on death rate by state and county in 2004. The effects of race, number of males per 100 females, population density, and age composition of the counties on the death rate were also considered.

## Variables
The dataset contained information on the following variables:
  
* Death rate: number of people who died/ 1,000 people
 * Income: average income in the county observed in USD
 * Physician rate: number of physicians in the county observed per 100,000 people
 * Population density: number of persons per sq. mile
 * Sex:  number of males per 100 females
 * Age composition: percent of total population that belongs to each respective age group (under 5, 5-14, 15-24, 25-34, 35-44, 45-54, 55-64, 65-74, 75+)
 * Racial composition: percent of total population that belongs to each respective racial group (White, African American, Hispanic or Latino, Native American or Native Alaskan, Native Hawaiian or other Pacific Islander, Asian)
 * State: the state of the observation
 * County: the county of the observation, nested inside State


# Results
Physician rate, income, all age categories except for 75 and over, Asain, and Hispanic or Latino are each associated with an estimated decrease in death rate. The percent of population age 75 and over, African American, and the interactions between Physician rate and African American, physician rate and Hispanic or Latino, physician rate and income are all associated with an estimated increase in death rate 



# License
For this github repository, the License used is [MIT License](https://opensource.org/license/mit/).
