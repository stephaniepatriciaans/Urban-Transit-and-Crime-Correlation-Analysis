# Urban Transit and Crime Correlation Analysis

This project explores the relationship between public transportation activity and crime incidents in two major U.S. cities: **Chicago** and **New York City**. By integrating spatial data from transit systems and crime reports, we investigate whether transit activity can help explain crime patterns using spatial regression techniques.

## Repository Structure

```
├── data/
│   ├── CTA_-_Ridership_-__L__Station_Entries_-_Daily_Totals.csv
│   ├── CTA_-_System_Information_-_List_of__L__Stops.csv
│   ├── Crimes_-_2001_to_Present_20250223.csv
│   ├── MTA_Subway_Stations.csv
│   ├── MTA_Subway_Turnstile_Usage_Data__2016.csv
│   ├── MTA_Subway_Turnstile_Usage_Data__2022.csv
│   ├── NYPD_DATASET_1.csv
│   ├── nypd.csv
│   ├── diff.txt
│   ├── riderChicStations.txt
│   └── sysChicStations.txt
├── Project_Proposal.ipynb       # Project planning and methodology
├── Data_Checkpoint.ipynb        # Data loading, cleaning, and preprocessing
├── EDA_Checkpoint.ipynb         # Exploratory data analysis and visualizations
└── Final_Project.ipynb          # Final analysis with spatial modeling and conclusions
```

## Objective

We aim to:

- Integrate diverse public datasets (CTA, MTA, NYPD, CPD)
- Preprocess and clean station-level transit and crime data
- Perform exploratory visual analysis and hypothesis testing
- Build spatial regression models (using PySAL and spreg) to detect patterns

## Prerequisites

- Python 3.7+
- Jupyter Notebook

## Installation

```bash
git clone https://github.com/stephaniepatriciaans/urban-transit-crime-analysis.git
cd urban-transit-crime-analysis
pip install -r requirements.txt
```

## Requirements

```text
pandas
numpy
requests
matplotlib
seaborn
geopandas
contextily
shapely
libpysal
spreg
statsmodels
```

## How to Use

1. Place the datasets inside the `data/` folder.
2. Launch Jupyter and run the notebooks in this order:
   - `Project_Proposal.ipynb`: Introduces the problem and goals
   - `Data_Checkpoint.ipynb`: Prepares and processes the data
   - `EDA_Checkpoint.ipynb`: Visual and statistical data exploration
   - `Final_Project.ipynb`: Builds and analyzes the spatial model

## Insights

The analysis reveals spatial clusters and correlations between transit usage and local crime density. We explore how geographic context and accessibility can play a role in shaping urban safety.


