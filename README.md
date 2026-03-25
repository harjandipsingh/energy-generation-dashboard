# Energy Generation Dashboard — Tableau

An interactive Tableau dashboard analyzing U.S. energy generation trends across grid regions, built using over 4.3 million hourly generation records.

## Live Dashboard
[Click here to view the interactive dashboard](https://public.tableau.com/app/profile/harjandip.singh/viz/Intel-Student_17679573474550/Dashboard)

## Project Overview
This project explores how energy is generated, distributed, and consumed across U.S. grid regions over time. The goal was to turn a large, raw dataset into a clear, interactive tool that lets users explore renewable energy trends, regional differences, and hour-by-hour production patterns.

**Central question:** How does renewable energy generation compare to total production across regions, and when does demand peak?

## Dashboard Features
- 7 worksheets covering generation by source, region, and time period
- 3-view layout with filters for Region, Energy Source, and Balancing Authority
- SelectPeriod parameter built with DATETRUNC — switch between day, week, and month views instantly
- Calculated metrics including Net Production, Renewable Energy total, Renewable Percentage, and Hour-over-Hour % Difference

## Dataset
| File | Records | Description |
|------|---------|-------------|
| energy_dataset.csv | 548,951 | Demand and net generation records |
| energy_dataset_long.csv | 4,391,608 | Hourly generation records by source and region |

## Tools Used
- Tableau Desktop
- DATETRUNC for time series grouping
- Table calculations for period-over-period analysis

## Key Findings
- Renewable energy share varied significantly by region and time of day
- Demand spikes followed predictable patterns tied to time of day and season
- Certain balancing authorities consistently showed higher renewable percentages, pointing to infrastructure differences across regions

## Author
**Harjandip Singh**
MIS Student — George Mason University
[LinkedIn](https://www.linkedin.com/in/harjandip-singh)
