# Coronavirus - (COVID-19) Full Stack Application
The idea behind this application is to displays the statistics of Coronavirus COVID-19 around the world and the data are being collected from  and it updates the cases constantly on this website around the world. 


And it uses Mapbox to populate the coordinates on the map using GeoJSON format.

<img src="Screenshots/covid19.png"/>

### MongoDB sample database import command
After git clone import the dummy statistics into your local MongoDB database, which will help you to start the project.

``````````````````````````
git clone https://github.com/anshumanpattnaik/covid19-full-stack-application.git

cd covid19-full-stack-application

mongod (Start MongoDB database)

mongoimport --uri "mongodb://127.0.0.1:27017/covid-19" --collection covid_statistics --file dummy_statistics.json
``````````````````````````

