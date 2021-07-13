[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/nttde/map-mazemap-demo)

# MAP MazeMap Demo

This Node-RED flow illustrates the potential of combining NTT Managed Automation Platform (MAP) and Cisco MazeMap for geolocation usecases.

Description of the demo: 

* GPS data has been taken from the [Microsoft Geolife Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=52367) and is hardcoded in the [flow](https://github.com/nttde/map-mazemap-demo/blob/master/MAP-MazeMap-demo-flow.json)
* NTT MAP (Node-RED) is used to serve the the web landing page with the MazeMap as well as the GPS coordinates of 3 arbitrary tracked objects
* Frontend (jquery) polls location data from Node-RED and updates the position of the markers in the MazeMap

![image](https://user-images.githubusercontent.com/7114726/124941616-37c74380-e00b-11eb-92c8-3199bb7d4e04.png)

![image](https://user-images.githubusercontent.com/7114726/124941726-50375e00-e00b-11eb-8864-10746806dba3.png)



## Use Case Description

Want to represent near-real-time gps locations in outdoor and indoor MazeMaps? This demo will show you how easy it is to build a feasible prototype. Now go on and substitute "X" with whatever you want(satellites, ships, people, dogs)We put the technology, the advantage is yours!

## Installation and usage
* [Install NodeRed](https://nodered.org/docs/getting-started/local)
* Import MAP-MazeMap-demo-flow.json
* Click deploy
* Browse http://{{your-node-RED-path}}/demo
* Near-Real-Time location data corresponding to the aboved mentioned dataset will be simulated on the demo

## Getting help

For any question please contact eu.de.devnet@global.ntt

## NTT Managed Automation Platform (MAP) is:
### A tool we use internally
MAP was developed for our Technical and Managed Services teams to automate their work, meanwhile used worldwide internally.
### A tool we use for our clients
We improve our processes to better manage client requests and to have better results by using MAP internally.
### A tool our clients use
We offer the same tool to our clients to automate their work for them, to co-create with them or just use what was already developed.
### It's not just a tool, it’s a journey
Automation is a journey, our internal methodology "Automation by Design" covers the whole automation lifecycle from finding automations, via the company and processes improvements, working agile to the MAP tool.

![image](https://user-images.githubusercontent.com/7114726/125426174-14e1c68a-b6b5-4668-b334-8601c0401fe1.png)


