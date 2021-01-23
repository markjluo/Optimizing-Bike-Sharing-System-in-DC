README.txt - a concise, short README.txt file, corresponding to the "user guide". This file should contain:
DESCRIPTION - Describe the package in a few paragraphs.
	In our project, we have:

	1. raw_data: the original data downloaded from Capital Bikeshare, a bike sharing company in Washington DC. In the folder 2018, we have all the trips' data, including each trip's duration, start time, end time, start station, end station, etc. 

	2. data_clean: clean the raw_data by eliminating the data which are not typical.

	3. output_data_cluster: we use kmeans and em algorithms to cluster the cleaned data and generated the cluster output into csv files.

	4. data_interpretation: further analyze the characteristics of each cluster by looking into the pickup and return pattern.

	5. imbalance_ratio: analyze the imbalance ratio of each station

	6. optimization: optimize the routes in each cluster for the truck to balance the bike station. 

	For our visulization, see part EXECUTION. 

INSTALLATION - How to install and setup your code.
	Download the compressed zip file and uncompress it. 
	If want to run our codes specifically, you can find them in each subfolder list above and run the jupyter notebook. 

EXECUTION - How to run a demo on your code.
	Localhost in our package folder, open the index.html, which is our home page for our project. You can use the navigation bar or the home page link below to tour around out visualization results. We have our Cluster Map, Data Interpretation Chart, Imbalance Ratio Map and Chart and Optimization Routes Map. 

	For map, chart: (which listed on the page as well)
		Single-click on the legend on the left to hide one class
		Double-click on the legend on the left to isolate one class
		Use mouse to zoom in and out on the map

