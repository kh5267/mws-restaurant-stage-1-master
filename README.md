#### _Three Stage Course Material Project - Restaurant Reviews_

Developer: Kevin Huibregtse
Date: 1/16/2019

## Project Overview: Stage 1

### Instructions

1. In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
   * Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
2. With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.
3. User can select a restaurant directly from the map or from the list below (via the "view details" button).
4. The restaurant list can be filtered by neighborhood and cuisine.
5. The restaurant details page shows the map location and reviews. The user can either click the title or breadcrumb to navigate back to the home page.
6. The app is responsive:
    a. The restaurant list columns are reduced as the viewport narrows.
    b. The filering options become a column rather than a row as the viewport narrows.
    c. On the details page, the map is moved underneath the image as the viewport narrows.
7. The app is accessible:
    a. The tab index begins with the filtering options, and continues through the "view details" buttons for each restaurant. Then it cycles back around to the map markers.
    b. Hitting enter with a map marker highlighted opens the restaurant details page.
    c. On the details page, initial focus allows the user to arrow down through the reviews. Tabbing takes you to the title and breadcrumb to return home.
8. The app works offline via service worker caching.

### Dependencies
https://api.tiles.mapbox.com/
https://www.openstreetmap.org/
https://creativecommons.org/licenses/by-sa/2.0/
https://www.mapbox.com/
//normalize-css.googlecode.com/svn/trunk/normalize.css
https://unpkg.com/leaflet@1.3.1/dist/leaflet.css


### Required Files
index.html, restaurant.html
css/styles.css
data/restaurants.json
img/1.jpg, 2.jpg, 3.jpg, 4.jpg, 5.jpg, 6.jpg, 7.jpg, 8.jpg, 9.jpg, 10.jpg
js/dbhelper.js, main.js, restaurant_info.js, sw.js


