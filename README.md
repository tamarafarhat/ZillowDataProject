# ZillowDataProject
An Exploration of Zillow Home Prices.

## Functions written 
I wrote functions that 
1) Find start year of uncleaned data. 
2) Make dictonaries of row items and their row index.
3) Convert years in string format to integers.
4) Take in uncleaned and unstructed price data and visualize in a standardized format.

## Analysis Done
I calculated appreciation rates from 1996 to 2016 and the completeness of the data for each city.

## Conclusions
Out of the top ten  highest appreciation rates, nine are from the state of California. Is this because homes in California have actually appreciated the most of anywhere else in the United States? Or is this because the data itself is biased, and many states lack data until much later years? For example, I know from personal experience that New York City has appreciated a lot over the past 20 years. However, it will not show up in the appreciation table because it is missing data until 2004. It will only show up as "Nan" value.

I looked at the completeness of data by state. If California is near the top of the list, it could be that California data is the most complete and that our appreciation calculations may just be being influenced by that.

California has about 19.5 years of data per city, which compares with an median of 18.5 years of data for the united states. Out of all the states, California has the 12th highest number of complete values. We can say that California does have more complete datasets than other states, and this is a possible contributing factor to California's high appreciation rate. However, other states that rank similarly to california in terms of missingness do not show up in the top appreciation rates. In fact, out of the top thirty appreciations, 27 are from California. It is highly unlikey that this occured by chance and is more likely to have arisen from other factors. Such factors could be Prop 13, a short supply of housing, favorable weather, and high paying employers in the entertainment and tech industries that drive up home prices in California.
