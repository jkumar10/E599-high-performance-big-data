For our random forest implementation, we take the 2006 airlines data provided by the Bureau of Transportation Statistics with 1 million unique observations

http://stat-computing.org/dataexpo/2009/the-data.html

Some of the input features are: 

| Attribute | Description | 
| --- | --- |
| CRSDepTime | CRS Departure Time|
|DepTimeActual| Departure Time|
|DepDelay|Difference in scheduled and actual departure.|
|DepDel15|Departure Delay 15 Minutes or More (1=Yes)|
|DepartureDelayGroups|Departure Delay intervals|
|DepTimeBlkCRS| Departure Time Block, Hourly Intervals|
|TaxiOut|Taxi Out Time, in Minutes|
|WheelsOff|Wheels Off Time (local time: hhmm)|
|WheelsOn|Wheels On Time
|TaxiIn|Taxi In Time, in Minutes|
|CRSArrTime|CRS Arrival Time|
|ArrTime|Actual Arrival Time|
|ArrDelay|Difference in scheduled and actual arrival|
|ArrDel15|Arrival Delay Indicator|
|ArrivalDelayGroups|Arrival Delay intervals|
|ArrTimeBlk|CRS Arrival Time Block, Hourly Intervals|
