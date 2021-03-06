WeatherBug API Demo App
-----------------------------------
Created lovingly for the developer community by Mashery.

http://www.mashery.com

http://developer.mashery.com


SYNOPSIS
==================================================================

This demo App provides a way to see the WeatherBug API in action. 
It's built using appMobi's Cross Platform Development Kit (XDK) that 
lets you create mobile apps for smartphones and tablets using standard 
web languages (HTML5, CSS, and JavaScript).

FEATURES
==================================================================

1. Uses WeatherBug's API to get weather forecast for the next 7 days 
based on your current Geo Location (Using appMobi's built in GeoLocation 
Detection API)
2. Uses WeatherBug's API to get weather forecast for the next 7 days 
based on a zip code.


GETTING STARTED
==================================================================

You will need the following to get started -

1. appMobi's XDK. Free Download - http://www.appmobi.com/?q=node/27
2. A WeatherBug API key (Register at http://developer.weatherbug.com/member/register).

OBTAINING THE API KEY
==================================================================

Before you can begin using this app, you need need to get an API key 
from WeatherBug at http://developer.weatherbug.com/member/register. 
This will also give you a Single Sign-On Mashery ID with access to 
hundreds of other APIs.


SETTING UP THE API KEY IN THIS APP
==================================================================

Once you have obtained your API key (use the WeatherBug REST XML Key), 
assign the API key to the variable api_key on line 1 of the file 
weatherbug.js, like so -

<pre>
	var api_key ='your_api_key_here';
</pre>

Note: It must be your WeatherBug REST XML API Key, not the GEO API Key.

ABOUT WEATHER BUG API
==================================================================

The WeatherBug API provides the world's best source for intelligent 
weather information. Tap into the datasource and develop your own 
customized weather apps. Learn more about the WeatherBug API at http://developer.weatherbug.com


WEATHER BUG DOCUMENTATION
==================================================================

To learn more about the data set provided by WeatherBug's API, you 
can read through the API documentation at 
http://developer.weatherbug.com/docs


ABOUT MASHERY API Network
==================================================================
This app is built using the WeatherBug API, part of the Mashery API 
Network. The Mashery API Network gives you access to hundreds of APIs 
with single sign-on (SSO) access. When you sign in at 
http://developer.mashery.com, access and manage all of your applications 
and API keys in one central location.


EXPLORE MORE APIs
==================================================================
Check out Mashery's API Network at http://developer.mashery.com/apis 
to explore other awesome APIs including NY Times, Klout, USA Today, 
Rotten Tomatoes and many more. 


SUPPORT
==================================================================
If you have any questions or need any help obtaining an API key, 
you can reach out to us at: developer-relations@mashery.com
