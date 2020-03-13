# delhi-metro-route-scraper

Scrape http://www.delhimetrorail.com/ for station routes, fares and timings. Uses the http://www.delhimetrorail.com/metro-fares.aspx endpoint. Used in the telegram bot [https://github.com/arush15june/DelhiMetroRouteBot](https://github.com/arush15june/DelhiMetroRouteBot).

## Features

- Async scraping
- In Memory Route Caching (To extend to persist on disk).
- Information like stations in route, time, fare, interchanges.