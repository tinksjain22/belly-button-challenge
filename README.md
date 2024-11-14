# Belly Button Biodiversity Dashboard

## Overview

This project is an interactive dashboard to explore the **Belly Button Biodiversity** dataset, which catalogs the microbes that colonize human navels. The dataset reveals a unique distribution of microbial species (operational taxonomic units, or OTUs) found in human belly buttons. A small subset of these OTUs is prevalent across the majority of people, while others are rare. This project visualizes the microbial data for individual samples, providing insights into microbial diversity.

## Project Structure

The project files are organized as follows:
- `index.html` - The main HTML file for the dashboard.
- `samples.json` - A JSON file containing microbial data.
- `static/` - A folder containing necessary JavaScript and CSS files.

## Features

This dashboard includes interactive features that allow users to:
1. **View a Horizontal Bar Chart** displaying the top 10 OTUs for the selected sample.
2. **View a Bubble Chart** representing each sample in terms of OTUs and their values.
3. **View Metadata** for the selected sample, displaying demographic information.
4. **Dropdown Menu** to select different samples and update the visuals accordingly.

The visualizations and interactivity are powered by **D3.js** and **Plotly.js**.

## Visualizations

1. **Horizontal Bar Chart**
   - Displays the top 10 OTUs for each individual.
   - Uses `sample_values` as values, `otu_ids` as labels, and `otu_labels` as hover text.

2. **Bubble Chart**
   - Shows all OTUs in a bubble chart for a given sample.
   - `otu_ids` are used for x-values and marker colors.
   - `sample_values` are used for y-values and marker sizes.
   - `otu_labels` are displayed as hover text.

3. **Sample Metadata**
   - Displays demographic information for the selected sample in a panel.
   - Automatically updates based on the selected sample.


## Prerequisites
- **Git** for version control.
- **Web Browser** with JavaScript support.


