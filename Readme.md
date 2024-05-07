### COVID Analysis Project

Welcome to the COVID Analysis Project! This repository focuses on analyzing COVID-19 data from the database `covid_analysis`, specifically the table `covid_deaths$`. Dive into the SQL queries provided to retrieve and analyze various aspects of COVID-19 data such as total cases, total deaths, population, vaccination rates, and more.

#### Queries Overview

1. **Total Cases vs Total Deaths**
   - Provides a comparison between total cases and total deaths globally.

2. **Death Percentage by Location (States)**
   - Calculates the percentage of deaths compared to total cases for locations containing the term "states".

3. **Likelihood of Dying by Country**
   - Calculates the likelihood of dying if contracting COVID-19 in each country.

4. **Cases Percentage by Location**
   - Calculates the percentage of the population that has contracted COVID-19 in each location.

5. **Total Cases vs Population**
   - Provides a comparison between total cases and population size in each location.

6. **Infection Rate by Population**
   - Identifies countries with the highest infection rates compared to their population.

7. **Total Deaths by Continent and Location**
   - Presents the total death count for each location and continent.

8. **Global New Cases and New Deaths**
   - Calculates global new cases, new deaths, and the percentage of new deaths compared to new cases.

9. **Vaccination Progress by Location**
   - Tracks the vaccination progress by location, showing new vaccinations and the rolling total of vaccinated people.

10. **Vaccination Progress using CTE and Temp Table**
    - Demonstrates vaccination progress using a Common Table Expression (CTE) and a temporary table.

#### View

- **percentpopulationvaccinated**
  - Creates a view to store data for later visualization, including continent, location, date, population, new vaccinations, and rolling people vaccinated.

#### Usage Instructions

1. Run the provided SQL queries against the `covid_deaths$` table in the `covid_analysis` database.
2. Analyze the retrieved data to gain insights into COVID-19 statistics, including cases, deaths, population, vaccination rates, and more.

Feel free to explore and contribute to this project! Let's combat COVID-19 together through data analysis and insights. 🌍💉📊
