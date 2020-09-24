# Project1

# Role of Agriculture in Climate Change

This project seeks to understand the complex relationship between agriculture and climate change. Agricultural production both contributes to climate change in the form of manufacturing and transportation, while also being directly affected by climate change’s meteorological consequences.

We first cleaned and examined available global agricultural production and emission data, then compared this to the weather patterns and crop production data on the United States. 

# How to navigate this repository:

Each section of the project has a folder:






#Sylvester code and output:
This has a notebook called ‘climate_api_notebook.ipynb’ which contains the code to create a sample of cities and request weather data for each city, merging them into a data frame and then exporting to csv.
The notebook called ‘Plotting_notebook’ contains all analysis done afterwards, creating visualizations based on the exported csv files and created the gmaps visualization of the city sample. The two were kept separate so that the plotting notebook could be run without the climate api key, but it will still require a google maps key. The ‘data files’ folder contains the exported csvs and any other csv data used. The ‘images’ folder contains screenshots of the created visualizations. The .gitignore prevents the ‘config’ file from being pushed. 



