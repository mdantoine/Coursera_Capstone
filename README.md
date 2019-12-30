# Battle-of-the-Neighborhoods Coursera_Capstone
This respository is using a Jupyter Noterbook with Python and  Markdown language for a Capstone Project
## Introduction

The battle of the neighborhoods will take place in Europe. The primary purpose of the battle is to show case what each country has to offer to a foreigner or current citizen that wants to open up a business or move to a different part of the country. This work will analyze three different countries in Europe. The countries I have chosen are France, Italy and Spain. I also chose three regions within each of those countries for the battle to take place. In the country of France, Paris with its region Île-de-France, Rome,  Italy and its region Lazio and Madrid, Spain. These are all the capitals of there perspective countries and would give unique data on the surrounds of each peculiar country. All are rich in history and offer unique forms of life styles. Each capital has over 2 million people living within its area. 

#### Background

France, Italy and Spain are famous tourist destinations in the world. All three of these counties are multicultural European Union members known for their hospitality. They are also known for being the financial districts within their areas. All three members of the European Union speak different languages. Currently there are many countries that have tourist attractions such as sites to see and places to eat. Tourism drives the economy of any country. Restaurants play an important role when attracting tourist. Every city is unique in what it offers to a foreigner that comes there on a business trip or vacation. Wherever there is food people like to eat in excellent restaurants. All three of these countries are known for their food. 


##### Problem

The towns or neighborhoods where the restaurants are set up determine how well a restaurant will do. The more foot traffic the better chances are the restaurant will be successful. It is viatl that the area be well known throughout the world for its food. This analysis is going to based on which town or neighborhood is the best place to open up a restaurant. 

## Data acquisition and cleaning

For this project I was unable to find the data in the csv format. Some of the data was only in text format in hugh data files from certain web sites. I downloaded several of these file in the format of txt file. I imported all three of the countries files into different excel files but the data contained within them was not what I was looking for to complete this project. 
The data I was able to use came from https://simplemaps.com/ which had all three of the countries I was working on for this project in csv format. This data was just on the cities within France. Italy and Spain. I did some other additional research on the most popular areas within France, Italy and Spain. Some additional information came from https://en.wikipedia.org/wiki/Main_Page containing specfic serch terms to gather the names of the towns / neighnorhoods for France, Italy and Spain. Additional data which was not in csv format was gather and combine with other excel files in csv format. 

### Data Cleaning
Once all the data was collected it was imported into three separte Pandas dataframe one each for the different countries. Some of the countries had the geo spatial coordinates information already within the csv files and others I has to acquire using geolocator within Pandas. Some of the visualizing of the towns / neighborhoods will come from Folium library. The  Foursquare API will be use to explore data on the specfic towns within each country. I will be using k-clustering from machine learning techniques.  



