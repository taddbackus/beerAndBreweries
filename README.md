# beerAndbreweries
## Repository for Doing Data Science Project 1
This project aims to gain insight on breweries across the US and the types of beer they make.
The report that follows will conduct an analysis of brewery data collected from all 50 states 
and Washington D.C. about 558 US Breweries and 2410 US craft beers. We will analyze beer 
bitterness and alcohol content by state, as well as, the relationship between the bitterness 
and alcohol content.

The steps and procedures taken for this analysis are detailed in the RMD file, as well as an 
HTML file that shows the same information in a cleaner format. We 
start by looking at basic summary statistics, visual graphics, and at the 
statistical differences between ABV (alcohol by volume) and IBU (International 
Bitterness Units). We also looked at the differences between IPAs and other 
types of Ales. 

The initial data provided were in two separate datasets, one for beers and one 
for breweries (detailed bleow), which were later combined into a single dataset.


## Data
### Beer: [Beer.csv](https://github.com/tadbackus/beerAndBreweries/blob/main/Data/Beer.csv)
![image](https://github.com/tadbackus/beerAndBreweries/blob/main/Pictures/Beer%20Data.PNG)
Name: Name of the beer  
Beer_ID: Unique identifier of the beer  
ABV: Alcohol by volume of the beer  
IBU: International Bitterness Units of the beer  
Brewery_ID: Brewery id associated with the beer  
Style: Style of the beer  
Ounces: Ounces of beer  

### Breweries: [Breweries.csv](https://github.com/tadbackus/beerAndBreweries/blob/main/Data/Breweries.csv)
Brew_ID: Unique identifier of the brewery  
Name: Name of the brewery  
City: City where the brewery is located  
State: U.S. State where the brewery is located  
