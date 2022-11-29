# Overview

In order to better myself as a software engineer, I chose to get some practical experience developing with ArcGIS by creating a map program.

This program is a map that displays pop-ups for all of the hospitals in the US, including helpful information such as phone number, address, and whether the hospital is open. It has capabilities for searching, finding by location, and getting directions. The data was retrieved from HIFLD Hospitals (link listed under Useful Websites), a hosted feature layer with the point locations of hospitals in the US and its territories.

Though my purpose in writing this software was largely to practice GIS mapping, it also provides useful information in the case of an emergency.

[Software Demo Video](https://youtu.be/cd5K-W2YCdA)

# Development Environment

This software was developed in VS Code using ArcGIS services.

Code was written in HTML with internal styling and scripting.

# Useful Websites

* [Display a Pop-Up](https://developers.arcgis.com/javascript/latest/display-a-pop-up/\)
* [Find a Route and Directions](https://developers.arcgis.com/javascript/latest/find-a-route-and-directions/)
* [HIFLD Hospitals](https://www.arcgis.com/home/item.html?id=f36521f6e07f4a859e838f0ad7536898)

# Future Work

* Modify search to only return hospitals from the feature layer
* Then modify search to return the hospital's pop-up
* Change the method of getting directions. Current setup is not very user-friendly