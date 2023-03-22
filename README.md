# 490CodingProject

Project Title: Enviornmental Impacts on South-East Lake Michigan Beach Erosion and Deposition

Name(s) of individual or team members
Team leader: P. Timothy Young Schragel
Not team leader 1: Shauny Jackson
Not team leader 2: Dalton Harris

Short 1-2 sentence summary
- Beaches (and/or dunes) along the south-eastern tip of Lake Michigan appear to have grown from 1985-2020, based on an early look from landsat images.
  We would like to find where and by how much the beaches and dunes have changed (based on region size), as well as potential enviornmental factors that contribute to this. 
  Additionally, we would like to locate potential clustering for the changes (or lack thereof).

Problem statement, question(s) and/or objective(s):
- Problem statement: How have beaches changed on the south-eastern tip of Lake Michigan from 1985-2020?
- questions/objectives:
	- If the beaches have changed, what are some of the potential causes?
		- Water level change
		- Storms
		- Lake freezing
		- Precipitation
		- current influences
- Future Objectives
	- Where are clusters of change located?
		- perhaps along jetties or national parks
	- Additional factors

Datasets you will use (with links, if available)
- landsat (5 & 8)		: https://earthexplorer.usgs.gov/
- water levels		: https://www.lre.usace.army.mil/Missions/Great-Lakes-Information/Great-LakesInformation-2/Water-Level-Data/
- High Winds		: https://www.ncdc.noaa.gov/stormevents/choosedates.jsp?statefips=91%2CLAKE+MICHIGAN
- Precipitation 		: 
- Ice 			:

----------------------------------------------------------------------------------
					Unsure of which links were used

	- https://www.weather.gov/wrh/Climate?wfo=iwx
		- This has a data table with monthly and annual sums of precipitation. However, I am unsure if its possible to download the data table.
		  The site says I need to go to NCEI (National Centers for Environmental Information) (link: https://www.ncei.noaa.gov/), but I am unsure how to find a narrowed data set.
- Ice
	- cool ice coverage with shape files (https://www.glerl.noaa.gov/data/ice/glicd.php?year=1985)
		- additionally there is a pdf and txt files with annual max coverage (https://www.glerl.noaa.gov/data/ice/#historical)
		- there is also daily averages, and we can get a range of time (in days) that there was ice coverage for each year (or 5 years) (https://www.glerl.noaa.gov/data/ice/glicd/daily/mic.txt)
-----------------------------------------------------------------------------------


Python packages:
Rasterio
Numpy
Pandas
Geopandas
Matplotlib
Gdal
RSGISLIB
SKlearn
jupyterlab

Planned methods/approach
1. Use landsat to identify where beach and dune erosion/deposition is taking place (primarily Tim)
2. Identify potential causes and create correlation matrices
    - Storm events or significant wind instances (Shauny)
    - Water currents (Shauny)			- nodata
    - Wave data (Shauny)			- nodata
    - Water levels (Shauny)
    - Precipitation (Harris)
    - Ice build/coverage (Harris)
    - Human Coastal Development (Harris)	- nodata
3. Identify potential clustering		- nodata
4. Potential regression model

Expected outcomes
- Growth in beaches and dunes
- Factor in or out potential causes
	- Rule out lake high
	- See if other variables effect beach size
- where are clusters of change

Any other relevant information, images/tables, references, etc.

References
- NOAA - GLERL (Great Lakes Environmental Research Laboratory)
- NCEI (National Centers for Environmental Information)