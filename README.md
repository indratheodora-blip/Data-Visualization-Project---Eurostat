# Data-Visualization-Project---Eurostat
This repository is intended to support the reproductibility of my Data Visualization project. After downloading the publicly available dataset from Eurostat, you can use the python code in this repository to create the prepared tables for the 2 data visualizations. 

## Steps
1. Download the dataset from [Eurostat](https://ec.europa.eu/eurostat/databrowser/view/isoc_ci_in_h__custom_19556165/default/table). Make sure you have the following variables included in the dataset before downloading it:
   * type of household: TOTAL, A1, A1_DCH, A2, A2_DCH, ALL_NDCH, ALL_DCH
   * time: all the available years 2002-2025   
2. Make sure you rename the downloaded dataset as "downloaded_custom_dataset.csv". Run the python code provided in this repository to generate the two datasets for the visualizations.
3. For the fist visualization, use Flourish and the dataset "dataset_for_first_viz.csv"
4. For the second visualization, use Datawrapper and the dataset "dataset_for_second_viz.csv"
