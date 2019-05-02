# Ford GoBike System Data Exploration
## by Oliver Garcia


## Dataset

> Ford GoBike is the Bay Area's new bike share system, with thousands of public bikes for use across San Francisco, East Bay and San Jose. Our bike share is designed with convenience in mind; it’s a fun and affordable way to get around town. The data analyzed is from January, February and March of 2019 and was downloaded from https://s3.amazonaws.com/fordgobike-data/index.html


## Summary of Findings

> There are some outliner values for duration_hour in the dataset, still the data shows an strong preferance for shor trips of 0.19 hours during weekdays and 0.27 hours during weekends.
For the rest of the analysis I will remove all records with duration_hour greater than 1 hour.
>
> The weekends total rent time is normally distributed across the whole day with its peak at 2pm.
>
> The weekdays total rent time have 2 busy hours at 8am and 5pm, for the next of the analysis we will focus only on 8am and 5pm of weekdays for being the times of highest demand.
> There is a lower total time of rental at 8am (175.07 hours) compared to 5pm (178.72 hours) but, more bikes are required at 8am because the users are more evenly distributed at this hour. In comparison users are more concentrated in the mission district and financial district of SF which are commercail districts at 5pm.
- This analysis shows that Ford GoBike requires a minimum of 1394 bikes to assure that a potential user will find a bike no further than 100 yards away 99% of the time. The 8am map and 5pm maps show how many bikes should be in each location during the busiest hours of the day.

## Key Insights for Presentation

> There is a lower total time of rental at 8am (175.07 hours) compared to 5pm (178.72 hours) but, more bikes are required at 8am because the users are more evenly distributed at this hour. In comparison users are more concentrated in the mission district and financial district of SF which are commercail districts at 5pm.
- This analysis shows that Ford GoBike requires a minimum of 1394 bikes to assure that a potential user will find a bike no further than 100 yards away 99% of the time. The 8am map and 5pm maps show how many bikes should be in each location during the busiest hours of the day.