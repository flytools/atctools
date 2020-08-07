# ATCTOOLS

A software to help virtual controllers

USERGUIDE

**CLEARANCE MODULE**

**INTRODUCTION**

The Clearance module (CL) provides a list of aircraft out of particular airport, each aircraft requires an analysis that includes:

1. Departure time - If the current time exceeds 30 minutes after the time informed in the TIME field of the FPL, a yellow stripe will be displayed; if the time exceeds 45 minutes, the orange color will be displayed;

2. Flight level - If the level / altitude is incorrect according to the semicircular rule for IFR and VFR flights, a yellow stripe will be displayed; If the level is incompatible with the IFR or VFR rule, red will be displayed;

3. Flight duration - If the ENDURANCE field is less than the EET + 30 minutes, an orange stripe will be displayed.

**SECTORFILE SELECTION**

The data obtained Online are compared with the SECTORFILE (.isc) selected to obtain the SIDS / WAYPOINTS valid for the airport under control.

**RULES**

Controlled airports and respective runways in use separated by space (One airport per line).

**LIST OF AIRCRAFTS**

CALLSIGN - Displays details of the FPL;

ARRIVAL - Displays the map with the flight route;

FLIGHT LEVEL - Displays the map with the flight route;

RUNWAY / SID - Displays all available exits for the selected airport / waypoint / runway;

WAYPOINT - Displays the waypoints available in the flight plan route and in the sectorfile;

SQUAWK - Generates a random and unique transponder code;

ARROW - functions to reload this aircraft, reload all aircrafts, copy the authorization in English and copy the authorization in Portuguese.

**FLIGHT PLAN DETAILS**

When clicking on the aircraft&#39;s CALLSIGN, the FPL will be displayed, with the flight details and the incorrect fields with YELLOW, ORANGE or RED color;

**WEATHER MODULE**

The WEATHER module allows you to calculate the runway in use and the transition level, based on ICAO and METAR obtained at https://tgftp.nws.noaa.gov/data/observations/metar/stations/%.TXT.

This is the prototype of a tool to be broad and include other features to facilitate ATCO service.

THANK YOU! ![](RackMultipart20200807-4-150pkyi_html_c715fa8ab6b461c5.png)
