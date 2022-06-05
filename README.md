## Music Recommendation System 

Website : https://music-app-r.herokuapp.com/

![alt text](https://github.com/misaaldsouza/music-recommendation-system/blob/main/images/front-end.PNG?raw=true)

The music recommendation system can predict and then offer the appropriate songs to the user based on the characteristics or features of music the user listens to.

### Installation
___
> ##### pip3 install streamlit
> ##### pip3 install pickle

similarly import the following libraries :
seaborn, matplotlib, plotly, base64, pandas, numpy, PIL, io & os.

streamlit is a front-end framework for data-driven websites. 

It is one of the most easiest frameworks to use for data science apps out there.


### Model :

The algortithm used here is K-Means clustering and one of the methods from distance measures is used i.e. Manhattan Distance, which we have used to calculate
the distance/similarities between the song entered by the user and the songs in the dataset. 

The features used to find the similarities are :

     'acousticness', 'artists', 'danceability’,
     'duration_ms', 'energy', 'explicit', 'id’, 
     'instrumentalness', 'key', 'liveness’, 
     'loudness', 'mode', 'name', 'popularity’, 
     'release_date', 'speechiness', 'tempo’, 
     'valence', 'year'

### Steps :

1. Open mrs.py file on a text editor
2. Make sure all the libraries are installed
3. Open cmd, locate to the file where mrs.py is located and run the following command
> ##### streamlit run mrs.py
It will open a browser and display the output !

### Output : 
![alt text](https://github.com/misaaldsouza/music-recommendation-system/blob/main/images/recommendations.PNG?raw=true)

The link on the song column once clicked will open spotify and start playing that particular song !

![alt text](https://github.com/misaaldsouza/music-recommendation-system/blob/main/images/sidebar-vis.PNG?raw=true)
