#  Restaurant Reviews
## Udacity Frontend Developer Nanodegree
---


## Project Overview: 

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

For this project I used **MapBox API** for rendering the _map_, I set-up a **service workers** for offline caching and set-up **accessibility tags** for _screen readers_. 


### How to run it locally

In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

* In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
* Note -  For Windows systems, Python 3.x is installed as `python` by default. To start a Python 3.x server, you can simply enter `python -m http.server 8000`.
* iF you are uysing VSCode editor you can press simultaneously _`CTRL + `_ to open the terminal and run python web server directly from the editor


## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

## Service Worker:

I want thanks **Matt Gaunt** for his fantastic article that help me on the creation of the [Service Worker](https://developers.google.com/web/fundamentals/primers/service-workers/)
