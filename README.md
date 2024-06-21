# Geographic Visualization of Farmers Markets across the US

## Project Overview

This project focuses on the analysis and visualization of data related to national farmers' markets. The main objective is to provide insights into the availability and accessibility of farmers' markets across different regions, and their support for various payment assistance programs like SNAP, WIC, etc.

## Data Sources
- **Farmers Markets Data**: [National Farmers Market List](https://data.world/rebeccaclay/national-farmers-market-list) (farmersMarkets.csv)
- **Geographical Data**: [US Counties GeoJSON](https://gist.github.com/sdwfrost/d1c73f91dd9d175998ed166eb216994a) (counties.geojson)

## Features

- **Custom Visualizations**: Generate maps showing various features of the markets across US counties.
- **Interactive Maps**: Use Altair for interactive visualizations and Matplotlib for static maps.
- **Species Category Filtering**: Dynamically filter visualizations based on services offered and dates markets are active.
- **Projection Handling**: Use custom projection handling to include/exclude regions like Alaska and Hawaii appropriately.

## Dependencies

- Python 3.8+
- GeoPandas
- Matplotlib
- Altair
- Jupyter Notebook

## Installation
Some installations are necessary to run the project as intended. Here's how to set up the project environment:

### Create the environment from the environment.yaml file
`conda env create -f environment.yaml`

### Activate the environment
`conda activate myenv`

### To install the necessary libraries, run:
`pip install geopandas matplotlib altair jupyter`

## Usage
To run the Jupyter notebook
`jupyter notebook visualization.ipynb`

## Project Structure
- [visualization.ipynb](https://github.com/saumyaphadkar24/FarmersMarket/blob/main/visualization.ipynb): Main notebook containing the analysis and visualizations.
- [farmersMarkets.csv](https://data.world/rebeccaclay/national-farmers-market-list): Data file with details on farmers' markets.
- [counties.geojson](https://gist.github.com/sdwfrost/d1c73f91dd9d175998ed166eb216994a): GeoJSON file for mapping counties.
- [poster.pdf](https://github.com/saumyaphadkar24/FarmersMarket/blob/main/poster.pdf): Poster for all the visualizations.

## Acknowledgments
Data provided by Rebecca Clay through Data World and contributions from the GitHub community for GeoJSON data.