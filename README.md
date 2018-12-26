# google-map-tracer
Calculate the time spent at a single location by day. This simple Python script generates a dataset for my other proejct [Quantify Your Year.](https://github.com/tanykim/quantify-your-year) 

## Download location history data from google
1. Sign in with your own data and download your Location History data from the [Google's Takeout page.](https://takeout.google.com/settings/takeout)
2. Save the zip file in the same folder. Unzip it. Then you'll see the location history as ```Takeout/Location History/Location History.json```.

## Setup the location and timezone
Open setup.local and replace place holders with your data. Follow the instruction in the file.
Then copy the setting to a Python file.

```
cp setup.local setup.py
```
 
 ## Run ```home-time-accumulator.py```
 
 This generates json file. Update the file location and name as needed, following comments in the file.
 
 ### Note
 Environment: Python 3.6