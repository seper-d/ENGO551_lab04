# ENGO551_lab04
ENGO 551 - Adv. Topics on Geospatial Technologies

- This project focuses on MQTT Protocol implementations within a Geoweb application.
- The user can use the following interface/webpage (https://seper-d.github.io/ENGO551_lab04/) to 
  establish connection to a server, subscribe to a topic, publish to a topic, and receive information from the topic.
- GeoJSON is implemented to acquire the user's location alongisde the tempearture at that location. These values are
  then sent to the topic.
	
# Instructions
- Use the following information to establish a connection to the server.
[Server: test.mosquitto.org]
[Port: 8081]
- Subscribe to the topic (course_name/your_name/my_temperature).
- Once subscribed, input the corresponding values for course name and name.
- Click "Get Location" for the map to get updated with your location and temperature.
- To access the messages, download and install MQTTX. 

# File Descriptions
- index.html: Contains the html and css code for the webpage.
- script.js: Contains the javascript code including the GeoJSON, poho and MQTT protocol functions and implemetnations
- static: contains images used in the html code.
