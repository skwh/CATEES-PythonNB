# CATEES iPython Notebook scripts
These scripts do various things with data freely avaliable from NASA DAACs. They mainly try and plot the data against maps.

### DAACRetrievalTutorial
This is an example showing the basic steps for pulling data from a DAAC's OPeNDAP server and then accessing its variables through netCDF.

Includes a few visualization examples, too.

### DataBrowserExample
This example creates a few widgets to make up a datepicker, which is then used to select SMAP data from NSIDC DAAC.

### DataVisExample2
Right now... this one just shows some of south america. No data or anything. I was trying to figure out Basemap's `pcolormesh` function.

### OrbitViewer
Imports SMAP data from a certain date and graphs its avaliablilty against a global map. 

### SimpleGraphExample 
Makes a meaningless graph of Sea Ice Fraction vs latitude from some SMAP data.

### SMAPDataVisExample
Attempts to graph same data from before, but on a South Polar Stereographic projected map. It doesn't go so well.

### SMAPMODIS_VegetationVsMoisture
In progress. Attemping to merge SMAP and MODIS data to visualize soil moisture vs vegetation greenness.

### TimeSeriesExtraction
Based on a date slider, obtains SMAP SP3 data for Simi Valley, CA and plots it.

### TimeSeriesExtraction2
In progress. Attempting to obtain MODIS data from 2000 to present and graph it for a specific section of the US.
