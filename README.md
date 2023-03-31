# Ocean State Spatial Database

This repository includes a collection of scripts used to generate layers and census data tables for the Ocean State Spatial Database (OSSDB), which is a collection of spatial layers and attributes for mapping and analyzing data in Rhode Island. The database has not been released yet; release is slated for summer 2023.

Most of the database layers are relatively static and only need to be updated once every ten years, as they are based on the decennial TIGER Line files and census data.  Some features are updated on an annual basis, where older data is swapped for the most recent release.  Scripts for these layers will be included in this repo:

1) Point features from that include colleges, public libraries, hospitals, and schools.

2) 5-year Census American Community Survey data for census tracts, ZIP code tabulation areas (ZCTAs) and county subdivisions (cities and towns).

3) 2020 Census data from the public redistricting files for census tracts and county subdivisions

4) OUTDATED and not yet updated for RI: Census ZIP Code Business Patterns data that includes total counts of establishments, employees, and wages, and counts of establishments by two-digit sector level NAICS codes at the ZCTA level (the script aggregates source data from ZIP Code-level).

5) Utilities for copying tables between different databases

Geodatabase features and tables that are meant to be updated every ten years were created manually. 
