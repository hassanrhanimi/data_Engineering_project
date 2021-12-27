#-------- Data_Engineering_project*-----------------------------------------------------------------------------------------------


This repository is composed of two mini-projects where we'll assume the role of a data engineer.

The goal is to explore and implement a type of batch processing called ETL standing for "Extract, Transform and Load".

ETL does exactly what the name implies. It is the process of

- Extracting large amounts of data from multiple sources (csv, json, xml, databases, html, ...) then
- Transforming it into one specific format, and
- Loading it into a database or target file.

#-------------------------------------------------First scenario-------------------------------------------------------------------
Assume working at a start-up devolopping an AI tool to predict if someone is at Risk for diabetes using height and body weight.
The goal is to implement an ETL to get data from multiple sources (csv, json, xml file format), transforming it and store it in 
a format acceptableby the AI.

A second exemple of car-dealer campany is also given.
The dataset contains CSV, JSON, and XML files (three from each format) for used car data which contain features named car_model, year_of_manufacture, price, and fuel. The Goal is to implement a simple ETL to collect, combine and transform data then store it
into one file for end-user (a data analyst, scientist for analysis or a BI enginner for ad-hoc reporting).

#-------------------------------------------------Second scenario------------------------------------------------------------------
Assume working for an international financial analysis company. the company tracks stock prices, commodities, forex rates, inflation rates.  the job is to extract financial data from various sources like websites, APIs and files provided by various financial 
analysis firms. After collectting the data, and extracting the data of interest to the company and transforming it based on the requirements given. I'll store the data in a csv file ready to be loaded into a database.

The project is splited into three parts:
- Webscraping
- Collecting data through an API and finally,
- Transforming the collected data into a ready-to-load format.

*Source : "Python Project for Data Engineering" course on Coursera by IBM
