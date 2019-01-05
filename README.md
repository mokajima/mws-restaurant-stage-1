# Restaurant Reviews App

Restaurant Reviews App is a website which is responsive, accessible, and available offline.

![Screenshot](https://mokajima.github.io/portfolio/images/restaurant-reviews-app.jpg)

## Dependencies

- [Leaflet](https://leafletjs.com/) v1.3.1
- [Mapbox](https://www.mapbox.com/) v4

## Install

Download the files from this repo and start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

Replace `<your MAPBOX API KEY HERE>` in `js/main.js` and `js/restaurant_info.js` with your Mapbox API key.

## Acknowledgements

- Udacity - provided the starter code
