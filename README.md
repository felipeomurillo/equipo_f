# equipo_f
COVID-19: Correlating impact with financial/health indicators

TEC Monterrey Data Bootcamp


Equipo F: Cecilia Acosta | Luis Bonilla | Felipe Murillo
May 16, 2020

------------------------------------------------------

## Motivation
Beginning at the end of 2019 and grossly picking up momentum in 2020, the world is currently facing a global COVID-19 pandemic caused by the SARS-CoV-2 virus. As of May 2020, COVID-19 has affected over 4 M people worldwide now claiming over 300 K lives.
* Is this pandemic impacting nations indiscriminately or are there regions more affected than others? 
* Should lower income countries be more exposed to COVID-19 cases and deaths?
* Are there specific correlations between mortality rates and factors such as health expenditure, number of hospital beds, and GNI?
* Are nations with high health expenditures and more hospital beds having lower mortality rates?

  
## Data Mining
### World Health Organization
  * COVID-19 cases per country (as of May 5, 2020)
  * Hospital Beds per 10,000 ppl
### World Bank Organization
  * Health Expenditures
  * $USD spent
  * % of gross domestic product (GDP)
  * Gross national Income (GNI) per capita – i.e., measure of standard of living
### REpresentational State Transfer (REST) Countries
  * ISO 3166-1 alpha-3 codes for country names

## Data Wrangling
* Employed two Jupyter Notebooks
  * Data mining and wrangling
  * Data visualization and analysis
* Import raw data from CSV files and APIs
* Extract points of interest and convert each data set into a DataFrame
* Merge data to create a single master data file (CSV):
  * 170 rows x 10 columns (indexed by = country)
  * Merging by country name was tricky --> used 3-letter country codes for cleaner merge
  
## Conclusions
* COVID-19 has widely spread around the globe with variable impacts across countries but hard-hitting Europe and the US.
* There is not high correlation between mortality rates and health expenditure, number of hospital beds and GNI, although we have some outliers per region and income bucket.
* Countries with the highest health expenditures do not necessarily have the most number of beds, which translates in different mortality rates. For instance, France, Sweden, Belgium, Netherlands, UK, Spain, and Italy are amongst the highest expenditures as % of GDP but also show high mortality rates (above 10%).
* No alarming mortality rates or high number of cases reported in low income countries (with also low health expenditures) which could be related to a) scarce information or b) lack of COVID tests ran in such geographies.

