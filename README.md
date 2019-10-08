# CityBusinessCentres_Prediction
#### In this project, we are going to predict business/market centres of a city using clustering.We have choosen city Mumbai for analysis and we have used k-Means clustering Algorithm for clustering of different amenities(bar,pub,cafe,etc..) into business centres

##### Getting Data of Mumbai
* Visit Overpass Turbo website(https://overpass-turbo.eu/) and perform query as shown in image after searching for Mumbai in search bar of Map:
![image](https://user-images.githubusercontent.com/33418013/66421686-f06ee600-ea25-11e9-9e1a-1db597b07eb7.png)

* Next, goto data tab, and then press export.Choose file type GeoJson and download geojson file of city data.
![image](https://user-images.githubusercontent.com/33418013/66422479-5f990a00-ea27-11e9-9e03-503fa7a94cb8.png)
![image](https://user-images.githubusercontent.com/33418013/66422608-996a1080-ea27-11e9-8308-98e32ec6b91e.png)
* Visit mygeodata website (https://mygeodata.cloud/converter/) to convert GeoJson file to .csv file (in this project this file is export.csv)
![image](https://user-images.githubusercontent.com/33418013/66422752-e5b55080-ea27-11e9-8b19-c2ae86cd17f5.png)

##### Converting csv file to point shapefile
* To convert csv file to point shapefile, visit https://mygeodata.cloud/converter/ , drag your .csv file and get your point shapefile from the converter.
##### Visualizing point shapefile of business centres (clusterCentroid.dbf)
![image](https://user-images.githubusercontent.com/33418013/66423021-6ffdb480-ea28-11e9-900a-f0f1fd72faa9.png)
##### Visualizing point shapefile of centroids of best clusters (best_clusterCentroid.dbf)
![image](https://user-images.githubusercontent.com/33418013/66423420-53ae4780-ea29-11e9-8595-40087129f65a.png)
