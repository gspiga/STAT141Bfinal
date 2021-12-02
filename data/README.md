# Datasets used in project:

## CDC COVID-19 Deaths by county and race
File name: `/cdc-deaths-by-county-and-race.csv`

[Source link](https://data.cdc.gov/NCHS/Provisional-COVID-19-Deaths-by-County-and-Race-and/k8wy-p9cg)

Variables:

    * Data as of: date MM/DD/YYYY
    * Start Date: date MM/DD/YYYY
    * End Date: date MM/DD/YYYY
    * State: string
    * County Name: string
    * Total deaths: integer
    * COVID-19 deaths: integer


## CDC Vaccine Hesitancy for COVID-19
File name: `/cdc-vaccine-hesitancy.csv`

[Source link](https://data.cdc.gov/Vaccinations/Vaccine-Hesitancy-for-COVID-19-County-and-local-es/q9mh-h2tw)

Variables:

    * FIPS Code: integer
    * County Name: string
    * State: string
    * Estimated Hesitant: float
    * Estimated hesitant or unsure: float
    * Estimated strongly hesitant: float
    * Social Vulnerabiilty Index (SVI): float
    * SVI Category: string


## State Abbreviations
File name: `/state-abbreviations.csv`

[Source link](https://www.ssa.gov/international/coc-docs/states.html)

Variables:

    * State Name: string
    * State Abbreviation: string


## State Political Parties
(Edited to remove excess heading and footer comments)

File name: `/state-political-parties.csv`

[Source link](https://www.kff.org/other/state-indicator/state-political-parties/?currentTimeframe=0&sortModel=%7B%22colId%22:%22Location%22,%22sort%22:%22asc%22%7D)

Variables:

    * Location: string
    * Governor Political Affiliation: string
    * Footnotes