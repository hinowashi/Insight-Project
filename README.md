# Insight-Project

In this project I intend to determine the cheapest way to win the Big Year competition by the American Birding Association (ABA), following their rules. As part of their rules they give the list of eligible birds (1116). All the birds have to be seen from 12:00 AM, January 1st to 11:59 PM, December 31st of the same year.

I will also minimize cost and maximize for weather conditions! In the hopes to have the best trip ever!!!

To do that I will use two years of data form the ebird citizend science project, that will hive bird observation in (x,y,t) for the hole US.  I will then transform this observation to a P_i(x,y,t) where P_i is the probability of seeing bird i in place (x,y) at time t.  The locations have been selected to be public places, e.g. national parks, state parks, wildlife refuges. 

The weather information will come form NOAA.  I will use historical data for each of the different locations.  I will prioritize sunny and not windy days form rany, cloudy and windy ones. This will increase the liklighood of having a good look at the bird and mabybe even having a great picture. 

The cost optimization will come last (I mean you are already planing to take a year of from work).  I will try to reduce airfare and acomodations costs.

The solution to the problem is a constrain programing one.  In the sence that we most see all the birds.  The weather and cost will be added as secondary incentives.  

Finaly this product will be individualized since it will take the user origin location and budgets constraints.
