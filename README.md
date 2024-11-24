# EDS220: Visualizing the Perimeter of the 2017 Thomas Fire

## About this project:
- This project was an assignment for EDS 220 for the Master's of Environmental Data Science (MEDS) program at UCSB in November of 2024.
  
- Using data from CAL FIRE, accessed via Data.gov, a boundary from the perimeter of the major wildfire that spread across the Thomas are in 2017 was created.
  
- Near-infrared, shortwave infrared, and red band data from Landsat 8 was utilized to create a false color map of the greater Sanata Barbara area that allows for ease of visualization of fire scars. 

## Repository Structure:
- There are two .ipynb files in this repository that both contain detailed steps on how to create the aforementioned Thomas Fire boundary and false color map, contained in the 'hw4-task2-fire-perimeter-Enda.ipynb' and hw4-task2-false-color-Enda.ipynb' files respectively.
  
- The data was complied into a folder labeled 'data' that was added to the .gitignore file so as to not overload github's capabilities, but links to the data will be provided below in the references section.

## Data:
#### California Wildfire data:
- This dataset was accessed on November 23, 2024 from the Data.gov website, but was originally complied from egis.CALFIRE. 
Please note that this file will contain the perimeters for many historic fires across California, not just the Thomas Fire.

- From the Data.gov website, the historic fire data can be loaded in as a GEOJSON file, as seen in the .ipynb files in this repository, or can similarly be loaded in as a shapefile, or csv. There are other options available for utilizing the data on various GIS applications. 

#### Landsat 8 data:


## References:
#### California Wildfire Data:
Data.gov. CAL FIRE, egis.CALFIRE. "California Fire Perimeters (all)", *State of California Catalog*. (2024). https://catalog.data.gov/dataset/california-fire-perimeters-all-b3436. date accessed: [11/23/2019]

#### Landsat 8 Data:
