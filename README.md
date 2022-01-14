# Exploratory Data Analyst-Project-Buffalo-Crime

Exploratory Data Analysis of Buffalo Crime Incidents public dataset from Open Data Buffalo website

by Thinh Ho

## Motivation

I am a junior majoring in Applied Mathematics and minoring in Computer Science. I am interested and planning to work as a Data Science after graduation. After completing the some Data-related courses on DataCamp, I decide to gain some hand-on experience working with data using some popular Python libraries such as Pandas, Numpy, and Matplotlib. Taking an inspiration from my university's location - State University of New York at Buffalo, for my first project, I will work with public dataset about crime incidents from Open Data Buffalo website to gain a better understanding from the city where I am living and studying.

## 1) Project Introduction

Thanks to Open Data Buffalo (https://data.buffalony.gov/), I am able to connect to API and retrive the dataset for my project. It consists three parts:
> - Data Cleaning
> - Exploratory Data Analyst
> - Insights

## 2) Data Cleaning

The data scraped needed to be cleaned up, so that it was usable for our model.

The following changes was made:
> - Remove undesired columns
> - Check for null values(missing data) and drop them because we cannot assume zip code and location
> - Uppercase all the values of the categorical columns to have correct numbers of unique value
> - Change datatype for incident_datetime, hour_of_day, and zip

## 3) Exploratory Data Analysis

I have tried to answer these questions with good visualiztions:

> - What types of incident happen the most ?
> - The Neighborhood with the most incident ?
> - When is the crime likely committed? ?

![INCIDENT](https://user-images.githubusercontent.com/80074386/149566749-738782da-d632-41d0-84c8-715eef9fb1ff.png)

Top 5 incident types include :
> - Robbery
> - Uuv
> - Burglary
> - Assault
> - Larceny/Theft
And Larceny/Theft is about double compare to the 2nd/3rd incident

![most crime](https://user-images.githubusercontent.com/80074386/149567003-c73682f3-a4d6-4dd4-a7a5-efc856763de1.png)
![least crime](https://user-images.githubusercontent.com/80074386/149567018-e4c2ed69-9218-4361-8199-1fedb47d20b9.png)

In general, there is no neighborhood with significant high crime rate in Buffalo.
On the other hand, there is a huge different between the least crime neighborhood and the most crime neighborhood. Therefore, there are some neighborhoods that are safer than others.

![hour](https://user-images.githubusercontent.com/80074386/149566911-a8abd2a8-aed5-4570-b5e3-3efb597896ef.png)

Crimes happen the most around 12AM midnight and 12pm midday comes secondly.

Crimes happen the least early in the morning from 4AM to 7AM.

There is no significant different for other hour during the day.

![day crime](https://user-images.githubusercontent.com/80074386/149567205-76228ae4-802b-4a86-af0d-8eb983e50964.png)


Crimes happen about the same everyday of the week.

Friday and Saturday is little higher compares to others.

![month crime](https://user-images.githubusercontent.com/80074386/149567144-f30c5c70-e3d3-4222-8daf-b83132553cb7.png)

Crimes happen the most on July and the least on February.

Compare to Winter (from December to March), there are more crimes on Summer (from June to September)

According to the Internet, February is the snowniest month in Buffalo, that maybe a reason we have the least crime on February.

![year crime](https://user-images.githubusercontent.com/80074386/149567412-1fb93ef1-aaf3-4c89-9497-df5640529508.png)

Overall, we have a good sign when the numbers of crime decline over year.


