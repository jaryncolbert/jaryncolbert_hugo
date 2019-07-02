---
title: "World of Recurse"
description: "A Map to Display and Find Recursers based on their Current Locations"
icon: "/projects/world-map.gif"
alt_text: "Recurse World Map Demo"
made_at_rc: true
rc_login_required: true
weight: 20
---

The last project that I worked on
at the [Recurse Center](https://www.recurse.com/) (RC)
was a map to display the locations
of members of the RC community
on an interactive world map.

The front-end was built in JavaScript
with [React](http://reactjs.org/);
the map is [Leaflet](https://leafletjs.com/),
with the Leaflet [MarkerCluster](https://github.com/Leaflet/Leaflet.markercluster) plugin
and [OpenStreetMap](https://www.openstreetmap.org/about) tiles.

The back-end
to retrieve data
from the [RC APIs](https://github.com/recursecenter/wiki/wiki/Recurse-Center-API)
(_RC login required_)
was written in Python
with [Flask](http://flask.pocoo.org/),
and it performs geocoding
with the [GeoNames](https://geonames.org) geocoder
via the [GeoPy](https://geopy.readthedocs.io/en/stable/) library.

[The code](https://github.com/jaryncolbert/recurse-world-map) is up on GitHub,
but it is currently not yet hosted online.
The GIF below shows a short demo of using the app,
with last names and overall location counts removed for privacy
(these details will only be made available
to members of the RC community via authentication).

![GIF demo of the World Map App](/projects/world-map.gif)
