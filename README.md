# DatathonTrack3

This is Datathon Track3 done by the Matrix team. In the data folder, raw India rainfall data from year 1951 to 2015 is included, which needs to be filtered to extract useful information to be used for analysis. In the Indian Rainfall Data Cleaning and Analysis notebook, data extracting is done, and an analysis of India rainfall trend with predictive models is done afterwards. In addition, a qgis containing rainfall aggregated to the district level in 1981 is made, having the ability to be transfered and used directly for other researches. Finally, a file geodatabase is included, containing maps of kernel density analysis in decade intervals that show how rainfall level changes in India from 1951 to 1990. In the process of generating these maps, first, one decade of rainfall data is grouped by each coordinate point to calculate the mean, and then raster analysis is performed for each individual dataset to calculate kernel density. This geodatabase is again, ready to be transfered and reused in other researches (due to export the color gradient of maps are changed into black and white, the user can just change  the desired color scheme back after opening).
