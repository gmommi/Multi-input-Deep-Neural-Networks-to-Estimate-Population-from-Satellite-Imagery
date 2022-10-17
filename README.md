# Multi-input-Deep-Neural-Networks-to-Estimate-Population-from-Satellite-Imagery
This repo contains the dataset used to train and test the network.

#### Structure:
- **Lazio** folder, including images covering Lazio (italian region) area:
  * *Tiles*: folder containing images to train and validate the network
  * *Test*: folder with images to test the network over the same area
  * *population*: excel file containing information about the dataset. Columns *i* and *j* identify the tile. In the name of each tile (i.e. img_0_18), the first number corresponds to the value of column *i*, while the second coincides with that of column *j*.
  
- **Grosseto** folder, including images covering Grosseto (italian province) area:
  * *Tiles*: folder containing images to test the network
  * *population*: excel file containing information about the dataset. Columns *i* and *j* identify the tile. In the name of each tile (i.e. img_0_18), the first number corresponds to the value of column *i*, while the second coincides with that of column *j*.
    
- **Napoli** folder, including images covering Napoli (italian province) area:
  * *Tiles*: folder containing images to test the network
  * *population*: excel file containing information about the dataset. Columns *i* and *j* identify the tile. In the name of each tile (i.e. img_0_18), the first number corresponds to the value of column *i*, while the second coincides with that of column *j*.
  
#### Image Features:
 - Satellite images taken by Sentinel-2A in the years 2015-2016
 - TCI RGB images with a 10m resolution per pixel and dimensions of 2km x 2km
 - Low cloud coverage
 - Geo-referenced images in the reference system UTM 32N/WGS84
 - Images selected at the top of the atmosphere (TOA)
 
#### Target Variable:
- Population values obtained by manipulating census section data, collected in the 2011 Italian census
 
 
