# Number of people by religion - Data package

This data package contains the data that powers the chart ["Number of people by religion"](https://ourworldindata.org/grapher/number-of-people-by-religion?v=1&csvType=full&useColumnShortNames=false) on the Our World in Data website.

## CSV Structure

The high level structure of the CSV file is that each row is an observation for an entity (usually a country or region) and a timepoint (usually a year).

The first two columns in the CSV file are "Entity" and "Code". "Entity" is the name of the entity (e.g. "United States"). "Code" is the OWID internal entity code that we use if the entity is a country or region. For most countries, this is the same as the [iso alpha-3](https://en.wikipedia.org/wiki/ISO_3166-1_alpha-3) code of the entity (e.g. "USA") - for non-standard countries like historical countries these are custom codes.

The third column is either "Year" or "Day". If the data is annual, this is "Year" and contains only the year as an integer. If the column is "Day", the column contains a date string in the form "YYYY-MM-DD".

The remaining columns are the data columns, each of which is a time series. If the CSV data is downloaded using the "full data" option, then each column corresponds to one time series below. If the CSV data is downloaded using the "only selected data visible in the chart" option then the data columns are transformed depending on the chart type and thus the association with the time series might not be as straightforward.


## Metadata.json structure

The .metadata.json file contains metadata about the data package. The "charts" key contains information to recreate the chart, like the title, subtitle etc.. The "columns" key contains information about each of the columns in the csv, like the unit, timespan covered, citation for the data etc..

## About the data

Our World in Data is almost never the original producer of the data - almost all of the data we use has been compiled by others. If you want to re-use data, it is your responsibility to ensure that you adhere to the sources' license and to credit them correctly. Please note that a single time series may have more than one source - e.g. when we stich together data from different time periods by different producers or when we calculate per capita metrics using population data from a second source.

### How we process data at Our World In Data
All data and visualizations on Our World in Data rely on data sourced from one or several original data providers. Preparing this original data involves several processing steps. Depending on the data, this can include standardizing country names and world region definitions, converting units, calculating derived indicators such as per capita measures, as well as adding or adapting metadata such as the name or the description given to an indicator.
[Read about our data pipeline](https://docs.owid.io/projects/etl/)

## Detailed information about each time series


## Number of people
who are Buddhists
Estimates of the number of people who are buddhists.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
who are Buddhists” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


## Number of people
who are Hindus
Estimates of the number of people who are hindus.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
who are Hindus” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


## Number of people
who are Muslims
Estimates of the number of people who are muslims.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
who are Muslims” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


## Number of people
who are Jews
Estimates of the number of people who are jews.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
who are Jews” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


## Number of people
who are Christians
Estimates of the number of people who are christians.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
who are Christians” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


## Number of people
who are not religious
Estimates of the number of people who are religiously unaffiliated.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
who are not religious” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* The religiously unaffiliated population includes people who say they do not identify with any religion or that they are atheist or agnostic in surveys and censuses.
* Some people categorised as “non-religious” or “religiously unaffiliated” may engage in activities and hold beliefs that can be considered religious or spiritual, even though they don't describe themselves as belonging to any religion. This is particularly important for Chinese data, since “religiously unaffiliated” is by far the largest group. Pew [discusses this](https://www.pewresearch.org/religion/2023/08/30/measuring-religion-in-china/) in detail.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


## Number of people
affiliated to other religions
Estimates of the number of people affiliated to other religions. Other religions include Baha'is, Daoists (also spelled Taoists), Jains, Shintoists, Sikhs, Wiccans, Zoroastrians and many small groups, some of which can be described as folk or traditional religions.
Last updated: October 31, 2025  
Next update: October 2026  
Date range: 2010–2020  
Unit: people  


### How to cite this data

#### In-line citation
If you have limited space (e.g. in data visualizations), you can use this abbreviated in-line citation:  
Pew Research Center (2025) – processed by Our World in Data

#### Full citation
Pew Research Center (2025) – processed by Our World in Data. “Number of people
affiliated to other religions” [dataset]. Pew Research Center, “Global Religious Composition Estimates for 2010 and 2020” [original data].
Source: Pew Research Center (2025) – processed by Our World In Data

### What you should know about this data
* These estimates are [sourced from](https://www.pewresearch.org/religion/2025/06/09/global-religious-change-methodology/) more than 2,700 censuses and surveys.
* People are categorized based on how they describe their own religious identity. If someone identifies with a religious group, they're classified as being part of that group regardless of their practices or beliefs.
* While censuses often provide information on people of all ages, most surveys only report on the religious composition of adults. In such cases, researchers use indirect demographic methods to estimate this data for children. For example, Pew uses data on the age structure and fertility rates of women in different religious groups to estimate the proportion of each religious group in the child population. This assumes that children share their mother's religion.
* Pew's methodology has changed over time, as improved data sources have become available. That means its latest estimates for 2010 — shown in this dataset — may differ from its earlier publications. You can see these changes and the reasons for these revisions in [its updated methodology](https://www.pewresearch.org/religion/2025/06/09/why-we-revised-our-estimates-for-2010/).

### Source

#### Pew Research Center – Global Religious Composition Estimates for 2010 and 2020
Retrieved on: 2025-10-31  
Retrieved from: https://www.pewresearch.org/dataset/dataset-of-global-religious-composition-estimates-for-2010-and-2020/  


    