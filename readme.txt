                       The Global Airport Database
                         Release Version 0.0.2

Author: Arash Partow

Copyright notice:
Free use of the Global Airport Database is permitted under the
guidelines and in accordance with the most current version of
the MIT License.
http://www.opensource.org/licenses/MIT


[INTRODUCTION]
The Global Airport Database (GADB) is a FREE downloadable database  of
9300 airports big and small from all around the world. The database is
presented in a simple token delimited format.

Field	Name	Type
01	ICAO Code	String (3-4 chars, A - Z)
02	IATA Code	String (3 chars, A - Z)
03	Airport Name	String
04	City/Town	String
05	Country	String
06	Latitude Degrees	Integer [0,360]
07	Latitude Minutes	Integer [0,60]
08	Latitude Seconds	Integer [0,60]
09	Latitude Direction	Char (N or S)
10	Longitude Degrees	Integer [0,360]
11	Longitude Minutes	Integer [0,60]
12	Longitude Seconds	Integer [0,60]
13	Longitude Direction	Char (E or W)
14	Altitude	Integer [-99999,+99999]
(Altitude in meters from mean sea level)
16	Latitude Decimal Degrees	Floating point [-90,90]
17	Longitude Decimal Degrees	Floating point [-180,180]

For more information please visit:

http://www.partow.net/miscellaneous/airportdatabase/index.html
