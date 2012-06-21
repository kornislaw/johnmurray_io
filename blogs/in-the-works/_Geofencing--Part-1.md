# The Series
Okay, so I've split this blog post into three parts. Don't worry, all of the
posts have already been written. I am splitting up the posts so that my readers
( _you_ ) can feel accomplished as they work there way through the sections.
Sometimes one über-long post can feel a little daunting. I've split it up as
follows:

- What is \[a] geofence/geofencing? \[[_this_][1] post]
- How to build your own geofence-server with Ruby and Mongo \[[link][2]]
- A walk-through of a sample geofence-server, built just for you \[[link][3]]

Let's get started shall we.

<br />
---
<br />

# What is \[a] Geofence/Geofencing?
## General Description
A geofence is a conceptual fence around some geographically defined area. For
example, the company I am currently working for deals in car-centric telemetry.
Specifically, we process a lot of geo-spatial data. We use this to allow users
to create a conceptual fence around their car (a geofence). When the car
reports outside of the fence, we can send them a notification. 

This is useful for making sure your car isn't stolen, tracking your children,
setting reminders for yourself, etc. If the idea of a conceptual fence is
still a little fuzzy, I'll draw you a pretty picture:

![pretty geofence picture][4]


## So Why Geofences?
talk about how spatially-aware apps are the future what with the rise
of mobile computing and possibly advertising and all that jazz

Let's face it, geofences are sexy. Apps that use user's geospatial data
is the next step in user-engagement. With geofences, we can interact with
our users when they're on the move; enjoying life and not spending countless
hours in front of a computer. 


## Computing Methods
Talk about various way of implementing a goefence
- break fences into grids
- ray-tracing algorithsm for point-in-polygon algorithms
- ??

Also, give some links to some geo-spatial indexing algorithms just
for completeness.


## Available Services
And finally, to wrap things up, here is a list of sites that provide
geofence services:

- [Geoloqi] (https://geoloqi.com/)
- [maponics] (http://www.maponics.com/trial-predefined-geofences-today/)
- [Urban Mappings] (http://www.urbanmapping.com/content/data-and-services)
- [Loc Aid] (http://www.loc-aid.com/)
- [locationlabs] (http://www.locationlabs.com/products/geofencing/)




  [1]: #
  [2]: /logs/pre/_Geofencing--Part-2.md
  [3]: /logs/pre/_Geofencing--Part-3.md
  [4]: /blog-files/geofence/fence_on_map.png