# License
This data was generated using data from the Redistricting Data Hub.  Any use of this project shall also comply with restrictions on use of data and attribution requirements set forth in the Redistricting Data Hub terms and conditions found at: [https://redistrictingdatahub.org/terms-and-conditions/](https://redistrictingdatahub.org/terms-and-conditions/).

Use of this project is further governed by the terms of the [Creative Commons Attribution Noncommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/legalcode.en)

# Wyoming Json and Shapefile

This json and shapeifle were created by Professor Ellen Veomett and her student Ananya Agarwal using the corresponding jupyter notebook.

# **Sources**
All data retrieved 05/29/24:

Obtain the following data from Restricting Data Hub

[Population data]( https://redistrictingdatahub.org/dataset/wyoming-block-pl-94171-2020-by-table/): based on the decennial census at the Census Block level on 2020 Census Redistricting Data

[State House District data](https://redistrictingdatahub.org/dataset/2022-wyoming-state-house-of-representatives-districts-approved-plan/): 2022 State House Approved Plan

[State Senate District data](https://redistrictingdatahub.org/dataset/2022-wyoming-state-senate-districts-approved-plan/): 2022 State Senate Approved Plan

[2020 election data](https://redistrictingdatahub.org/dataset/vest-2020-wyoming-precinct-and-election-results/)**:**  VEST 2020 wyoming precinct and election results

[2018 election data](https://redistrictingdatahub.org/dataset/vest-2018-wyoming-precinct-and-election-results/)**:**  VEST 2018 wyoming precinct and election results

[2016 election data](https://redistrictingdatahub.org/dataset/vest-2016-wyoming-precinct-and-election-results/  )**:**  VEST 2016 wyoming precinct and election results

## Processing
Data were cleaned and aggregated in the corresponding jupyter notebook using MGGG’s python library [maup](https://github.com/mggg/maup).  

# **Metadata**

Below is a brief description of each of the listed variables in the attribute table of the VTD shapefile:

- `STATEFP20`: State FIPS code
- `COUNTYFP20`: County FIPS code
- `VTDST20`: Voting tabulation district FIPS code
- `NAME20`: Voting tabulation district name
- `SEND`: State Senate district for 2021 State Senate Adopted Plan
- `HDIST`: State House district for 2024 State House of Representatives Districts Plan
- `TOTPOP`: Total population in 2020 Census
- `NH_WHITE`: White, non-hispanic, population in 2020 Census
- `NH_BLACK`: Black, non-hispanic, population in 2020 Census
- `NH_AMIN`: American Indian and Alaska Native, non-hispanic, population in 2020 Census
- `NH_ASIAN`: Asian, non-hispanic, population in 2020 Census
- `NH_NHPI`: Native Hawaiian and Pacific Islander, non-hispanic, population in 2020 Census
- `NH_OTHER`: Other race, non-hispanic, population in 2020 Census
- `NH_2MORE`: Two or more races, non-hispanic, population in 2020 Census
- `HISP`: Hispanic population in 2020 Census
- `H_WHITE`: White, hispanic, population in 2020 Census
- `H_BLACK`: Black, hispanic, population in 2020 Census
- `H_AMIN`: American Indian and Alaska Native, hispanic, population in 2020 Census
- `H_ASIAN`: Asian, hispanic, population in 2020 Census
- `H_NHPI`: Native Hawaiian and Pacific Islander, hispanic, population in 2020 Census
- `H_OTHER`: Other race, hispanic, population in 2020 Census
- `H_2MORE`: Two or more races, hispanic, population in 2020 Census
- `VAP`: Total voting age population in 2020 Census
- `HVAP`: Hispanic voting age population in 2020 Census
- `WVAP`: White, non-hispanic, voting age population in 2020 Census
- `BVAP`: Black, non-hispanic, voting age population in 2020 Census
- `AMINVAP`: American Indian and Alaska Native, non-hispanic, voting age population in 2020 Census
- `ASIANVAP`: Asian, non-hispanic, voting age population in 2020 Census
- `NHPIVAP`: Native Hawaiian and Pacific Islander, non-hispanic, voting age population in 2020 Census
- `OTHERVAP`: Other race, non-hispanic, voting age population in 2020 Census
- `2MOREVAP`: Two or more races, non-hispanic, voting age population in 2020 Census
- `AUD18D`: Number of votes for 2018 Democratic auditor candidate
- `AUD18R`: Number of votes for 2018 Republican auditor candidate
- `AUD18O`: Number of votes for 2018 other party's auditor candidate
- `GOV18D`: Number of votes for 2018 Democratic gubernatorial candidate
- `GOV18R`: Number of votes for 2018 Republican gubernatorial candidate
- `GOV18O`: Number of votes for 2018 other party's gubernatorial candidate
- `HAL16D`: Number of votes for 2016 Democratic US House candidate
- `HAL16R`: Number of votes for 2016 Republican US House candidate
- `HAL16O`: Number of votes for 2016 other party's US House candidate
- `HAL18D`: Number of votes for 2018 Democratic US House candidate
- `HAL18R`: Number of votes for 2018 Republican US House candidate
- `HAL18O`: Number of votes for 2018 other party's US House candidate
- `HAL20D`: Number of votes for 2020 Democratic US House candidate
- `HAL20R`: Number of votes for 2020 Republican US House candidate
- `HAL20O`: Number of votes for 2020 other party's US House candidate
- `PRE16D`: Number of votes for 2016 Democratic presidential candidate
- `PRE16R`: Number of votes for 2016 Republican presidential candidate
- `PRE16O`: Number of votes for 2016 other party's presidential candidate
- `PRE20D`: Number of votes for 2020 Democratic presidential candidate
- `PRE20R`: Number of votes for 2020 Republican presidential candidate
- `PRE20O`: Number of votes for 2020 other party's presidential candidate
- `SOS18D`: Number of votes for 2018 Democratic Secretary of State candidate
- `SOS18R`: Number of votes for 2018 Republican Secretary of State candidate
- `SOS18O`: Number of votes for 2018 other party's Secretary of State candidate
- `SPI18R`: Number of votes for 2018 Republican Superintendent of Public Instruction candidate
- `SPI18O`: Number of votes for 2018 other party's Superintendent of Public Instruction candidate
- `TRE18D`: Number of votes for 2018 Democratic Treasurer candidate
- `TRE18R`: Number of votes for 2018 Republican Treasurer candidate
- `TRE18O`: Number of votes for 2018 other party's Treasurer candidate
- `USS18D`: Number of votes for 2018 Democratic senate candidate
- `USS18R`: Number of votes for 2018 Republican senate candidate
- `USS18O`: Number of votes for 2018 other party's senate candidate
- `USS20D`: Number of votes for 2020 Democratic senate candidate
- `USS20R`: Number of votes for 2020 Republican senate candidate
- `USS20O`: Number of votes for 2020 other party's senate candidate

## Projection
This shapefile uses a NAD83(Harn)/UTM zone 17 North projection (EPSG:3747).
