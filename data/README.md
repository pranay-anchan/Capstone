
# Temporal Datasets
## Weather
## Holiday
## Weekdays
## Events (Potential)

# Spatial Datasets
## Taxi Zone Attributes
- 'OBJECTID'/ 'LocationID': Taxi zone ID
- 'Shape_Leng': Taxi zone length
- 'Shape_Area': Taxi zone area
- 'borough': NYC borough number

## ACS Census
- 'DensityPop': Population Density
- 'IncomePerCap': Income per capita ($)
- 'Poverty': under poverty level rate (%)
- 'Professional': % employed in management, business, science, and arts
- 'Service': % employed in service jobs
- 'Office': % employed in sales and office jobs
- 'Construction': % employed in natural resources, construction, and maintenance
- 'Production': % employed in production, transportation, and material movement
- 'Employed': employed rate (16+) (%)
- 'Unemployment': Unemployment rate (%)

- 'Drive': % commuting alone in a car, van, or truck
- 'Carpool': % carpooling in a car, van, or truck
- 'Transit': % commuting on public transportation
- 'Walk': % walking to work
- 'OtherTransp': % commuting via other means
- 'WorkAtHome': % working at home
- 'MeanCommuteMean': commute time (minutes)

## Crime
- 'FELONY': Number of felony crimes in the taxi zone
- 'VIOLATION': Number of violation crimes in the taxi zone
- 'MISDEMEANOR': Number of misdemeanor crimes in the taxi zone

## Transportation
- 'subway': Number of subway entrances
- 'bus': Number of bus stops

## Education
- 'sat': Average score of SAT reading, math, and writing.

## Parking
- 'meter': Number of merter parking.
- 'parkinglot': Area of parking lot.

## Potential Datasets
- BBL
- Park
- Parking Regulation Locations and Signs
- Meter parking price
- Garage parking price
- Google POI
- Yelp

***
# Data Source
## TLC’s for-hire vehicle data on TLC’s website  
  * https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page

## Parking ticket data from NYC open data
  * https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2019/pvqr-7yc4  
  * https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2018/a5td-mswe  
  * https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2017/2bnn-yakx  
  * https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2016/kiv2-tbus  
  * https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2015/c284-tqph  
  * https://data.cityofnewyork.us/City-Government/Parking-Violations-Issued-Fiscal-Year-2014-August-/jt7v-77mi  

### Problem:
no specific coordinate  
### Alternative solution:
  * Street Code1, Street Code2, Street Code3; Street Name  
  * Violation Location
Street name Dictionary:  <https://data.cityofnewyork.us/City-Government/Street-name-Dictionary/w4v2-rv6b>

## Parking garage revenues
Not available yet.

## Parking meter/muni revenue
Not available yet.

## Other parking data
  * Parking Lot shp: https://data.cityofnewyork.us/City-Government/Parking-Lot/h7zy-iq3d
  * parking garage list: https://data.cityofnewyork.us/Business/parking-garage-list/5bhr-pjxt
  * Parking Regulations shapefile: https://www1.nyc.gov/html/dot/html/about/datafeeds.shtml#parking
  * Parking Regulation Locations and Signs: https://data.cityofnewyork.us/Transportation/Parking-Regulation-Locations-and-Signs/xswq-wnv9
