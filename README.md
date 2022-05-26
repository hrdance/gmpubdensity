This script creates a map depicting density of pubs per square km in each Lower Super Output Area of Greater Manchester

How to run this code:

Load the gmpubdensity.ipynb into a jupyter notebook. You will need pandas, geopandas and matplotlib installed. Next download necessary data:

list of pubs:
https://www.getthedata.com/open-pubs
Put open_pubs.csv in same directory as the .ipynb

Postcode lookup:
https://geoportal.statistics.gov.uk/datasets/ons::national-statistics-postcode-lookup-may-2022/about
Put the following files in the same directory as the .ipynb:
NSPL_FEB_2022_UK_BL.csv
NSPL_FEB_2022_UK_M.csv
NSPL_FEB_2022_UK_OL.csv
NSPL_FEB_2022_UK_SK.csv
NSPL_FEB_2022_UK_WA.csv
NSPL_FEB_2022_UK_WN.csv

LSOA shapefile
https://webarchive.nationalarchives.gov.uk/ukgwa/20160110200248/http://www.ons.gov.uk/ons/guide-method/geography/products/census/spatial/2011/index.html
Get the 2011 LSOA boundaries - Generalised (20 metres), clipped to the coastline dataset.
Put the following files in the same directory as the .ipynb:
LSOA_2011_EW_BGC_V2.dbf
LSOA_2011_EW_BGC_V2.shp
LSOA_2011_EW_BGC_V2.shx

The code should now run, and output a file gmpubdensity.png with the created map.

Feel free to share, copy, re-use this code, but please give me credit if you publish it.

Contact: harryrdance@gmail.com