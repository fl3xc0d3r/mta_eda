# mta_eda
New York MTA turnstile data analysis, EDA

## Project Proposal


### Motivation:

1. WomenTechWomenYes would like to leverage the traffic and NYC's subway station to both spread awareness for as well as gather funds to support inclusion of women in technology. My team would like to use the MTA sample data to provide insights to their marketing team to optimize placement of resources in order to meet both of the above goals (spread awareness and get more people to attend the WTWY gala and donate
2. For 1. above, we plan to get basic statistics about highest foot traffic per station, as well as trends for such stations covering and increase or decrease in traffic, year over year, busiest times, etc.
3. The biggest event of this decade has been the covid 19 pandemic, and its effects have been felt on multiple industries. We would like to use freely available infection stats data and vaccine rollout data to investigate the affect on foot traffic. During the recovery, has foot traffic increased for all stations? Are the 5 highest stations still seeing the highest foot traffic? 

### Data:

The data we plan to use is freely available MTA turnstile data at web.mta.info, the AWS data lake for covid statistics at https://datascience.nih.gov/covid-19-open-access-resources and NYC covid vaccination data at https://github.com/nychealth/covid-vaccine-data/tree/main/doses

Our aim is to predict the best places (MTA stations) to be for WTWY marketers, as well as best times, while taking into account the pandemic of 2020 and subsequent recovery in 2021

### Tools:

We plan to use SQL to query useful data from datasets, pandas for EDA and matplotlib for visualization

### MVP:
An MVP would be an identification of the subway stations that have the most traffic, correlated with those whose traffic is increasing month by month. For these we will also include the top 3 busiest times
