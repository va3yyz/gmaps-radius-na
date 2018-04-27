gmaps-radius
============

This very simple little web app allows you to draw circles on top of a Google Map, with a radius that you specify.

[Try it out](//obeattie.github.io/gmaps-radius/?lat=43.739698&lng=-79.310305&z=11&u=km&r=1).


Query parameters
----------------

This tool supports the following optional query parameters:

* `lat`: Viewport center latitude
* `lng`: Viewport center longitude
* `z`: Default zoom level
* `r`: Default circle radius
* `u`: Default circle radius units

What You Need To Know About The Radius Tool

The tool loads the map data from Google Maps, that means it’s just the same but with the radius ring feature added on top.
You can not only draw one circle, you can draw several circles on the map.
The site allows you to change the radius value.
It supports different units, for example miles, nautical miles, kilometers, metres, feet, inches, yards and a few other units.
You can enable a terrain mode for the standard map and you can disable the map labels when using the satellite map.
A radius is simply added with a left-click, and removable with a right-click.
