# Bikesharing

## Overview

In this analysis, we will use Citi Bike utilization ride data from August 2019 to inform investors whether there is a good case to start a bikesharing program in Des Moines.

## Findings
 ### Who are the Citi Bike Users?
 Citi Bike distinguishes users by the following two types: annual subscribers ("Subscribers") and customers who pay for single rides or day passes ("Customers").
 
 In August 2019, out of 2,344,224 total Citi Bike rides, 81% were by subscribers.
 
 <img width="526" alt="Screen Shot 2022-06-01 at 4 32 00 PM" src="https://user-images.githubusercontent.com/100495799/171496224-8fbbb706-be70-4be5-a410-54279db5bff5.png">

Furthermore, 65% of the rides were booked by users who identified as "Male". Citi Bike system does allow for optional input for gender hence for customers or subscribers who chose not to disclose this data, their gender is marked as "Unknown".
<img width="390" alt="Screen Shot 2022-06-01 at 4 32 46 PM" src="https://user-images.githubusercontent.com/100495799/171496353-50cb70db-1774-4521-ae68-0d71d73fd004.png">

Overall, the highest percentage of subscribers are in the 30-39 age range (at 41%) while the highest percentage of customers are between 30-39 age range at 40% with 20-29 following closely at 38%.

<img width="978" alt="Screen Shot 2022-06-01 at 4 36 27 PM" src="https://user-images.githubusercontent.com/100495799/171496913-9564b27c-b8af-4579-877a-53e00fe1cb36.png">

## What are the top 10 Trip Starting and Ending Station

With Approximately 800 stations across NYC (and parts of NJ), the highest volume of trips starting and ending both located on the **island of Manhanttan**.

<img width="988" alt="Screen Shot 2022-06-01 at 4 49 48 PM" src="https://user-images.githubusercontent.com/100495799/171499014-fb829d0d-4bbd-48d4-9dd6-0220d601dfc8.png">
<img width="990" alt="Screen Shot 2022-06-01 at 4 50 49 PM" src="https://user-images.githubusercontent.com/100495799/171499157-cc868806-f321-4628-a51e-ccffaf4f8bbf.png">

## What are the most popular day(s) of week and hours of day for bike utilization?

For this particular analysis, we'll need to distinguish between Subscribers and Customers because their behaviors are somehow opposite of each other.

In the subscriber group, you will see heavier usage during rush hours between 8-9AM and then 4-7 PM.  These are likely the residents who are using Citi Bike for work commute.  This group also uses Citi Bikes more during the work week (Monday-Friday).

On the contrary, in the customer group, you will observe heavier usage later in the day between 11:00 AM - 7:00 PM.  These are assumed to be visitors enjoying the city.  This group uses Citi Bikes more on the weekends (Saturday-Sunday).
<img width="1011" alt="Screen Shot 2022-06-01 at 5 18 54 PM" src="https://user-images.githubusercontent.com/100495799/171503642-9d84d671-3ec5-41de-a7a1-a93a514c2462.png"><img width="822" alt="Screen Shot 2022-06-01 at 5 21 07 PM" src="https://user-images.githubusercontent.com/100495799/171503925-97b97979-d298-49e1-ba3b-1a240986c607.png">

## Summary

In conclusion, while one month of ride share data is somewhat insightful, I recommend further analysis to determine whether the ride share model is a good return in investment in a city that has a very small fraction of NYC's population.  For comparison purposes, the population in NYC is ~8.4 million in 2020 and Citi Bike has ~1.9 million subscribers.  That's roughly 23% of total population.  Des Moines has ~215k in population in 2020, so if we assume the same percentage of population as subscribers (not considering other factors such as local infrastructure, topography, radius of city center, etc), we would expect to have 49k subscribers, which may or may not make financial sense for our investors.
