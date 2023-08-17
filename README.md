# Game-Data-Engineering-model


![image](https://github.com/harshita-mohan/Data-Engineering-model/assets/22547288/ca5e8e4d-bcd4-4126-a490-7242a5b61707)


From the image we can understand the basic architecture of the project. The main services used in this project is :

1)Created storage account 

2) Data Factory
   
4) Resource group
   
4)Azure Databricks 

6) Synapse analytics 

DATA SOURCE- this is were we get raw data. DataSource is a name given to the connection set up to a database from a server. The name is commonly used when creating a query to the database. The data source name need not be the same as the filename for the database.

DATA FACTORY- In data factory we build data pipeline, basic transformation, complex queries. 

DATA LAKE STORAGE GEN 2- this is where we store raw data. We have uploaded csv file into this folder before we can make transformations.

DATABRICKS- this where we code to make changes in the raw data. We can query using multiple languages . in this project we have used apache spark to code. 

AZURE SYNAPSE ANALYTICS- use notebooks, use SQL to find some queries according to the project. 

Data understanding: 

The data is downloaded from kaggle website where it contains 11k records of athletes who play for plympics in tokyo. The file format is in xlsx but its changed to csv. there are 5 datasets- athletes, coaches, entries gender, medals, teams. 

1) Athletes- Personname, country, discipline

2) Coaches- Name, Country, Discipline, Event.

3) Entriesgender- Discipline, Female, Male, Total.

4) Medals- Rank, Team country, Gold, Silver, Bronze, Total, Rank_by_total.

5) Team- Team name, Discipline, Country, EVent.


Some other services used is : 

IAC Azure account 

Engineer subscription 

Dev resource group, product resource group 

Vm scale sets, Vnet, Azure Sql


The final output of the project is 

![image](https://github.com/harshita-mohan/Data-Engineering-model/assets/22547288/f1e18969-eb40-4899-aba6-07349884a57b)









