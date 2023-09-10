# SolarCalc
**Working on this app now - far from complete**

A web app for accurately calculating solar panel output (accounting for weather/conditions) and battery charge level. This app is primarily designed for "vanlife" applications, i.e. for calculating charge information for solar panels flat-mounted to the roof of a campervan which may be travelling to various locations. However, it may also be of use for domestic and commercial purposes.

The user shall provide the following information to the app:
* Location and elevation (can be accessed programmatically via GPS).
* Solar array total wattage (the app will assume flat-mounted panels).
* Height of solar panels above ground level (van height).
* Battery capacity.
* Expected power usage information (users provide a list of devices, their wattages, and the times they will be in use).

With this information, the app's main functions will be:
* To accurately forecast solar charging at the user's location, accounting for time of day, elevation, and weather/conditions.
* To accurately forecast battery charge level, accounting for solar charging and expected power usage.
* To accurately calculate if and when the battery charge level will next reach zero, to assist in planning for hookup or alternator charging.
* To display this information in an appealing and user-friendly way, such as through forecasting graphs and diagrams.

Once complete, the app will be hosted online.
