# postcode-finder

This site uses Google API to return the postcode of any address in the world. The aim of this project was to get more familiar with external APIs, in this case the Google Maps API, and accessing data via this method. 

The Google Maps API return data in an XML format, so it get me exposure to working with this particular data structure as well. I have worked with JSON more than XML in the past. The site itself is pretty simple with the API doing much of the heavy lifting. 

There was less emphasis on the design and look of the site. However, to ensure things looked presentable, I relied on Bootstrap for many of the elements. I also got a nice, high-res image from unsplash.com to sit in the background. jQuery is used to display and hide alerts to the user - this done using fadeIn() and fadeOut().

There is some basic validation on the site. If a postcode can’t be found, it prompts the user to check their spelling. Also, if nothing is entered, it prompts the user to enter an address.The site uses AJAX to load data, so the site does not refresh when fetching and retrieving data from the Google Maps API.
