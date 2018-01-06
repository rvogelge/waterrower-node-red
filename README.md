# waterrower-node-red

This application is implemented on a Raspberry Pi 3 with standard Noobs installation of Raspian

This node red flows can be used: 
- to read workout data from the Waterrowers USB interface
- save this data into a SQLite database
- and upload the workout to Strava 

Currently, there are no different types of workouts available. You can just start rowing.
On the dashboard you will see: 
- the distance
- time elapsed 
- total stroke count 
- and the average stroke rate per minute

## Installation:
Just import all node into noder red. Should be 2 Tabs with serveral links between.
The application detects if a WR is plugged in the USB port of the RPi
Just start rowing and save your workout after you have finished

## Required modules/nodes (in addition to the default modules):
- node-red-contrib-globalgetset
- node-red-contrib-usb
- node-red-dashboard
- node-red-node-sqlite

## Helpfull informations:

how to get write permission to Strava:

http://yizeng.me/2017/01/11/get-a-strava-api-access-token-with-write-permission/
