# leaflet-map-flickr-precision
testing precision level of iphone photo exif data as mapped by flickr

## Demo
- https://surduromeo.github.io/Barlad/.

able to display photos at zoom level 19, max of OpenStreetMap

## Basic steps
- take closeup photos with smartphone, with location (EXIF) settings on
- upload photos to a free Flickr account, add titles, and tag (eg. cemetery)
- set up a free GitHub account; learn to fork (copy) this code and host your own version on GitHub Pages (see http://DataVizForAll.org)
- edit this Leaflet map code to set location coordinates and set flickrURL to your account and tag

### Pros:
- easiest method

### Cons:
- requires all photos to be stored and auto-mapped in Flickr, which is not long-term plain
- no way to easily search data about photos

## To do: Explore alternate better method
- collect photos with EXIF location data
- manually name files in this format: 1800-Smith-Jane.jpg
- use exiftool to batch extract EXIF data (lat,lon coordinates) and year, name from title into spreadsheet CSV
- upload all photos and data into Leaflet map folder to display coords
- find plugin or write code to search/filter markers by date, text search
