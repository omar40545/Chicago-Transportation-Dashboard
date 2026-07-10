# Chicago Traffic Safety & Transit Infrastructure Dashboard

A GIS + Power BI dashboard analysing traffic crash patterns and CTA transit 
ridership across Chicago, built using public open data from the City of 
Chicago Data Portal.

## Overview

This project analyses 111,000+ traffic crash records (July 2025–July 2026) 
and 3 years of CTA ridership data to surface infrastructure risk patterns 
relevant to transportation planning and civil engineering work — the kind 
of analysis that supports agencies like IDOT, the Illinois Tollway, CDA, 
and CTA.

## Dashboard Preview

![Dashboard Overview](outputs/dashboard_overview.png)

## GIS Crash Map

![Crash Map](outputs/layout.pdf)

Built in ArcGIS Pro using XY Table to Point geocoding on crash coordinate 
data, styled by injury severity.

## Key Findings

- 111,019 crashes recorded with valid coordinates over the analysed period
- 26,000+ reported injuries; 97 fatalities
- The majority of crashes occur in daylight conditions, suggesting volume-driven 
  rather than visibility-driven risk
- CTA ridership shows a seasonal pattern, peaking in spring and dipping 
  through the summer months

## Data Sources

- [Traffic Crashes - Crashes](https://data.cityofchicago.org) — City of 
  Chicago Data Portal
- [CTA - Ridership - Daily Boarding Totals](https://data.cityofchicago.org) 
  — City of Chicago Data Portal

Raw crash dataset (111K+ rows) not included in this repo due to file size; 
available via the City of Chicago Data Portal link above, or on request.

## Tools Used

- **Python (pandas)** - data cleaning, filtering, type conversion
- **ArcGIS Pro** - geocoding, spatial visualization
- **Power BI** - interactive dashboard, KPI cards, trend analysis
- **Git/GitHub** - version control and project hosting

## About

Built by Omar as a self-directed portfolio project to demonstrate GIS and 
business intelligence capability applicable to civil engineering and 
transportation planning contexts.
