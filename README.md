I wanted to display the current and forecast weather data on my home website which I use to display monitoring graphs and controls for home automation. I looked at other sources of this data with full documented APIs but I just see to many variances in the weather data and really wanted to go straight to the source being the Australian BOM data.

BOM provide json feeds for their current weather but not for forcast data, so I had to scrape the HTML of the forcase page and parse the data and extract what I wanted.

This solutions uses a mix of JSON, CORs, YQL, and jQuery.

## Australian Bureau of Meteorology (BOM) Data Feeds
JSON Weather Feeds for cities and towns - http://www.rogerclark.net/json-data-from-www-bom-gov-au-a-work-in-progress/
XML Forecast Feeds for cities and towns - http://www.bom.gov.au/catalogue/data-feeds.shtml
