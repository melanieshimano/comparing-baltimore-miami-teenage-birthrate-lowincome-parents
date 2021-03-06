# Comparing Teenage Birth Rates of Females with Low-Income Parents in Baltimore, MD to Miami, FL
## Background
  The article [Socioeconomic Disadvantage as a Social Determinant of Teen Childbearing in the U.S.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3562742/) finds that "unfavorable socioeconomic conditions" are a contributing factor to high teen birth rates in the US. Teenage births are associated with adverse outcomes for both child --preterm birth, low birthweight, and infant death-- and mother, depending on her specific circumstances.  
  
  This topic is interesting because although teenage birth rates in the US have decreased, the _absolute_ teenage birth rate is still high. In 2010, the teenage birth rate was a low 34.3 births per 1,000 people. However, absolute teenage births were still high at 370,000 total teenage births in the same year. Further research is necessary to tackle the factors that influence teen pregnancy and to identify any possible interventions. 
  
  This project explores open data from the Opportunity Atlas Group on teenage birth rates of females from low-income families in Baltimore, MD and Miami, FL. The data takes teenage birth rates from tracts within neighborhoods in each city; several tracts can make up a neighborhood.
  
  ## Business Question
How do the teen birth rates from females in low-income families in Baltimore, MD and Miami, FL compare?

![map baltimore](https://user-images.githubusercontent.com/70858878/93527342-b7faac00-f906-11ea-98fa-94bce6585781.png)
![map miami](https://user-images.githubusercontent.com/70858878/93527382-c9dc4f00-f906-11ea-9789-ecd7afbe4f54.png)


## Data Sources
1. Opportunity Atlas
  - [Miami](https://github.com/vickidecastro/comparing-baltimore-miami-teenage-birthrate-lowincome-parents/blob/master/shown_tract_teenbirth_rP_gF_p25%20miami.csv): Original open data on teenage birth rates of females from low-income families in Miami, FL
  - [Baltimore](https://github.com/vickidecastro/comparing-baltimore-miami-teenage-birthrate-lowincome-parents/blob/master/shown_tract_teenbirth_rP_gF_p25%20baltimore.csv): Original open data on teenage birth rates of females from low-income families in Baltimore, MD
  - Teenage birth rate is defined as the fraction of women who claimed to have had a child while the mother was between the ages of 13-19, who also claimed dependent status. It is important to note that these estimates have a margin of error and that any time "Teen" or "Teenage birth rate" are mentioned, this refers to the birth rate of teenage girls coming from low-income families.
  - Some teen birth rates from specific tracts in neighborhoods in Baltimore, MD and Miami, FL were missing from the data set. 
  
  ## Data Analysis and Answers
  ### What are the mean teen birth rates in each city? 
  - Exploring average teen birth rates in each city using basic Excel functions
  ### What are the maximum and minimum teenage birth rates in each city?
  - Exploring highest and lowest rates of teen birth using basic Excel functions
![Picture1](https://user-images.githubusercontent.com/70858878/93416145-2b52de00-f873-11ea-9478-609798f14195.png)

  <img width="800" alt="Screen Shot 2020-09-16 at 8 29 04 PM" src="https://user-images.githubusercontent.com/70858878/93405593-5e897300-f85b-11ea-81da-5f568364e5e7.png">
 
 ### Which neighborhoods in Miami and Baltimore have the top 5 highest average teenage birth rates? 
  - Exploring areas with the highest average teen birth rates usig Pivot Tables, data reorganization, and vlookups. Averages have been taken from the tracts within each neighborhood.
![highestavgteenbirthrates](https://user-images.githubusercontent.com/70858878/93407568-862f0a00-f860-11ea-9091-5c5d36fe6495.png)

  ### What is the parental income level? 
 - Low-income families are defined as in the bottom 25% of the income distribution. 

## Overall Process
<img width="844" alt="Screen Shot 2020-09-16 at 8 02 52 PM" src="https://user-images.githubusercontent.com/70858878/93404989-c212a100-f859-11ea-8241-ab672cd1dab3.png">

## Summary
- The findings show that, on average, teenage birth rates of females from low-income families tend to be higher in Baltimore than in Miami. 
- The mean and maximum teen birth rates in Baltimore were higher than in Miami. 
- The areas with the top 5 highest average teen birth rates were higher than the top 5 areas in Miami. 
- Additional data on _specific_ income levels of families in neighborhoods would be helpful. 

