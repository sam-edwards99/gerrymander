# gerrymander

All of the code I wrote exists in main.py.
I had some issues with uploading the shapefiles since github said they were too big.
I managed to download the state borders shapefile as well as a CSV with the coordinate ranges of each state.

### Here is how my file structure looked in pycharm when I had all of the files stored locally (Files in bold are already available in the repo):
---------------------------------------------------------------
**main.py**

rivers/USA_Rivers_and_Streams.shp 

**state_shapes/cb_2018_us_state_500k.shp** \
**state_shapes/statebounds.csv** 

data/tl_2018_us_cd116.shp

---------------------------------------------------------------

The state_shapes directory contains the state borders shapefile as well as a CSV with the coordinate ranges of each state. This directory alreay exists in the repo.

The data directory contained the US districts shapefile which is available in zip file at 
https://catalog.data.gov/dataset/tiger-line-shapefile-2018-nation-u-s-116th-congressional-district-national/resource/2f03b54f-999d-44aa-9e52-e14013010551

The rivers directory contained the major rivers shapefile which is available at.
https://www.arcgis.com/home/item.html?id=8206e517c2264bb39b4a0780462d5be1


## Other Notes
 I am skeptical of using the US rivers data file as it is very large and might include too many small streams so currently this is commented out and only state borders are being used.


