# Create a map of WhatsApp members

The purpose of this notebook is to map WhatsApp chat members on a map.  It will do the following:

* Scrape the phone numbers from the WhatsApp chat log
* Extract either country code or US/Canada area codes from the phone number
* Associate the country/area code to a latitude and longitude using public data
* Map the latitudes and longitudes on a world map using Folium