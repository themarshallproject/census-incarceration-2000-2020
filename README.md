# incarceration-census

The Marshall Project extracted the number of adults in correctional facilitates from the [2000](https://www.census.gov/data/developers/data-sets/decennial-census.2000.html), [2010](https://www.census.gov/data/developers/data-sets/decennial-census.2010.html) and [2020](https://www.census.gov/data/developers/data-sets/decennial-census.2020.html) Decennial Census. The county-level data is used for the story [There Are Fewer People Behind Bars Now Than 10 Years Ago. Will It Last?](https://www.themarshallproject.org/2021/09/20/there-are-fewer-people-behind-bars-now-than-10-years-ago-will-it-last) by Weihua Li, David Eads and Jamiles Lartey. 

According to the [Census Bureau's definition](https://www2.census.gov/programs-surveys/decennial/2020/technical-documentation/complete-tech-docs/summary-file/2020Census_PL94_171Redistricting_StatesTechDoc_English.pdf), "correctional facilities" include federal detention centers like immigration detention centers, federal and state prisons, local jails, correctional residential facilities like halfway houses, and military jails. 

The file includes these fields:

* `state`: State postal codes
* `county`: County name
* `FIPS`: 6-digit FIPS code for the county
* `total_population_20`: Total population of the county in the 2020 Census
* `incarcerated_20`: Number of incarcerated people in correctional facilities as of the 2020 Census.
* `total_population_10`: Total population of the county in the 2010 Census
* `incarcerated_10`: Number of incarcerated people in correctional facilities as of the 2010 Census.
* `total_population_00`: Total population of the county in the 2000 Census
* `incarcerated_00`: Number of incarcerated people in correctional facilities as of the 2000 Census.
