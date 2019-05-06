# Data-Wrangling-Project-S2019
My final class project for MSDS 597 - Data Wrangling and Husbandry (Spring, 2019) at Rutgers University.

<br>

### Description of "ehmann-pje36-project.Rmd"

[8-16] Necessary R libraries.

[20-311] Code to scrape, format, and export data.

[315-881] Code for data analysis and visualization.

<br>

### Description of "smoking_data.csv"

357 rows (51 states x 7 rows per state)

28 columns

<br>

### variable [source] description (type)

state [1] US state (txt)

abbr [1] state abbreviation (txt)

region [8] US region (txt)

division [8] US sub-region (txt)

year [1] year (int)

percent [1] self-reported % of smokers (dbl)

state_int [-] intercept coefficient of lm(percent ~ year) for data grouped by state (dbl)

state_slope [-] slope coefficient of lm(percent ~ year) for data grouped by state (dbl)

state_resid [-] residual of lm(percent ~ year) for data grouped by state (dbl)

division_int [-] intercept coefficient of lm(percent ~ year) for data grouped by division (dbl)

division_slope [-] slope coefficient of lm(percent ~ year) for data grouped by division (dbl)

division_resid [-] residual of lm(percent ~ year) for data grouped by division (dbl)

region_int [-] intercept coefficient of lm(percent ~ year) for data grouped by region (dbl)

region_slope [-] slope coefficient of lm(percent ~ year) for data grouped by region (dbl)

region_resid [-] residual of lm(percent ~ year) for data grouped by region (dbl)

tax_2011 [2] tax ($) per carton of cigarettes in 2011 (dbl)

tax_2017 [2] tax ($) per carton of cigarettes in 2017 (dbl)

delta_tax [2] change in tax from 2011 to 2017 (dbl)

num_of_preemptions [3] count of main preemptions {max = 4} (int)

bar_restrictions [4] restrictions on smoking in bars (txt)

work_restrictions [4] restrictions on smoking in private workplaces (txt)

restaurant_restrictions [4] restrictions on smoking in restaurants (txt)

funding_per_capita [5] funding received ($) for smoking cessation per state citizen (dbl)

expenditures_per_capita [5] money spent ($) for smoking cessation per state citizen (dbl)

percent_funding_used [5] percentage of funding used (dbl)

fee_for_service_plans [6] information on state offered fee-for-service plans for cessation (txt)

managed_care_plans [6] information on state offered managed care plans for cessation (txt)

quitline_calls_per_10000 [7] total calls to the state quitline per 10000 people (dbl)

<br>

### Sources

[1]  CDC Behavioral Risk Factor Data: Tobacco Use (2011 to present)
https://chronicdata.cdc.gov/Survey-Data/Table-for-STATE-System-Current-Cigarette-Use-Among/xmxq-jxrr

[2] CDC STATE System Tobacco Legislation (Tax)
https://chronicdata.cdc.gov/Legislation/CDC-STATE-System-Tobacco-Legislation-Tax/2dwv-vfam

[3] CDC STATE System Tobacco Legislation (Preemption)
https://chronicdata.cdc.gov/Legislation/CDC-STATE-System-Tobacco-Legislation-Preemption/xsta-sbh5

[4]  CDC STATE System Tobacco Legislation (Smokefree Indoor Air)
https://chronicdata.cdc.gov/Legislation/CDC-STATE-System-Tobacco-Legislation-Smokefree-Ind/32fd-hyzc

[5]  University of Illinois at Chicago Health Policy Center (Funding)
https://chronicdata.cdc.gov/Funding/University-of-Illinois-at-Chicago-Health-Policy-Ce/vw7y-v3uk

[6]  Medicaid Coverage of Cessation Treatments and Barriers to Treatments
https://chronicdata.cdc.gov/Cessation-Coverage-/Medicaid-Coverage-Of-Cessation-Treatments-And-Barr/ntaa-dtex

[7]  Quitline Service Utilization (2010 to present)
https://chronicdata.cdc.gov/Quitline/Quitline-Service-Utilization-2010-To-Present/equ4-92qe

[8]  List of Regions of the United States (Wikipedia)
https://simple.wikipedia.org/wiki/List_of_regions_of_the_United_States
