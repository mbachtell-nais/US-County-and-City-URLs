# United States Counties/Parishes and Cities/Towns with URLs
Python scripts to pull the URLs of counties, parishes, and cities for the states and territories of the United States from Wikipedia.  This is driven from the Wikipedia table found at https://en.wikipedia.org/wiki/List_of_United_States_counties_and_county_equivalents and the individual list of cities, towns, etc... on each state page, such as https://en.wikipedia.org/wiki/List_of_municipalities_in_North_Carolina.

* The counties.py script will output a CSV of the county name, state, and URL.
* The cities.py script will output a CSV of the city, county name, state, and URL of a given city/town

## Command line use
### Counties
`python main.py process-cities`

### Cities
`python main.py process-counties`

### Process Counties and Cities
`python main.py process-both`

### Help
`python main.py --help`
