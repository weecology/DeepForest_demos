# DeepForest_French_Guiana
A DeepForest application repo for testing against the drone data from tropical forest in French Guiana. Response to Aubrey-Kentz 2019.

Aubry-Kientz, M., Dutrieux, R., Ferraz, A., Saatchi, S., Hamraz, H., Williams, J., Coomes, D., Piboule, A., Vincent, G., 2019. A Comparative Assessment of the Performance of Individual Tree Crowns Delineation Algorithms from ALS Data in Tropical Forests. Remote Sens. 11, 1086. https://doi.org/10.3390/rs11091086

# Installation

```
virtualenv -p python3 DeepForest
source DeepForest/bin/activate
pip install DeepForest
pip install git+git://github.com/bw4sz/keras-retinanet.git

```

Optionally add the dependencies for creating shapefiles and viewing the jupyter notebooks

```
pip install jupyter shapely geopandas
```

Due to data sharing agreements, the remote sensing source data is not available for this repo.
