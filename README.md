![alt text](http://transportforcairo.com/wp-content/themes/TfC-Theme/img/logo.png "Transport for Cairo")
# Metro GTFS

### This data contains: 
  The 3 Metro Lines of Cairo

### Data is released as:
  General Transit Feed Specification (GTFS)

You can see the data in action using Open Trip Planner [otp.transportforcairo.com](http://otp.transportforcairo.com). OTP will be available until the 8th of March 2016.

### What is GTFS?
The General Transit Feed Specification (GTFS) defines a common format for public transportation schedules and associated geographic information. GTFS "feeds" allow public transit agencies to publish their transit data and developers to write applications that consume that data in an interoperable way.

### What files are in the GTFS?
agency.txt	      	One or more transit agencies that provide the data in this feed.
stops.txt	        	Individual locations where vehicles pick up or drop off passengers.
routes.txt	      	Transit routes. A route is a group of trips that are displayed to riders as a single service.
trips.txt	        	Trips for each route. A trip is a sequence of two or more stops that occurs at specific time.
stop_times.txt	   	Times that a vehicle arrives at and departs from individual stops for each trip.
calendar.txt	    	Dates for service IDs using a weekly schedule. Specify when service starts and ends, as well as days of the week where service is available.
calendar_dates.txt	Exceptions for the service IDs defined in the calendar.txt file. 
shapes.txt	      	Rules for drawing lines on a map to represent a transit organization's routes.
frequencies.txt	  	Headway (time between trips) for routes with variable frequency of service.
feed_info.txt	    	Additional information about the feed itself, including publisher, version, and expiration information.

#### GTFS Schema:
This schema shows how the GTFS files are connected to each other.

![alt text](http://transportforcairo.com/wp-content/uploads/2016/02/GTFS-Schema.png "Transport for Cairo GTFS-Schema")

### Important Note?
All data related to schedules and dates are estimations.


For more information about GTFS [check](https://developers.google.com/transit/gtfs/) or email us at info@transportforcairo.com for questions.

Data is available under the Creative Commons Attribution-NonCommercial 4.0 International Public License.
