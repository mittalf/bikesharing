# bikesharing
Bike sharing project using Tableau

## Overview of the Project

Kate used bike-share in NYC while vacationing and is now interested in starting a bike share business in Desmoine, Iowa. She has found a potential angel investor who is interested in providing seed investment to explore a bike share program in Desmoine.
First she needs to figure out how the Bike-Share program actually works in NYC. From there create a proposal on how it will work in Desmoine.


### Project Background:

Some of the questions to ask are:
1. How many trips were recorded during the month of August? Determine the number of trips.
	Total number of trips in August: 2,344,224
2. How does ridership grow over time? The Proportion of Short Term Customers to Annual Subscribers
	
3. How many bikes we might need in Des Moines? D uring which parts of the day we'll need the most bikes. For example, if we need to do maintenance on a bike, knowing the peak usage hours will help us plan for the best time to do that.Peak riding hours in the month of August 
	
4. What Are the Top Bike Stations in the City for Starting a Journey? Highest traffic locations to understand where people use Citi Bike
5. Find Top Ending Locations
6. Find the Number of Rides by Gender
7. Find the Average Trip Duration by Age: The general trend is that younger riders tend to use the bikes for longer periods of time. 
   The later the birth year, longer the bike ride.
8. Determine the Bikes Due for Repair. The bikes used most frequently will probably be the ones that require the most maintenance
9. Determine Bike Utilization. How long the bike rides are.

Tableau NYC Citi Bike Dashboard:

[NYC Citi Bike Dashboard](https://public.tableau.com/app/profile/falguni.mittal/viz/NYCCitiBikeDashboard_16423750428630/NYCCitiBikeDashboard?publish=yes)

### Purpose

The purpose is to convince investors that a bike-sharing program in Des Moines is a solid business proposal. To solidify the proposal, one of the key stakeholders would like to see a bike trip analysis.

- Length of time that bikes are checked out for all riders and genders
- Number of bike trips for all riders and genders for each hour of each day of the week
- Number of bike trips for each type of user and gender for each day of the week

## Resources:

- Data (201908-citibike-tripdata.csv.zip) - (Citi Bike System Data page -- Citi Bike Trip Histories - downloadable files for Citi Bike trip data) - https://ride.citibikenyc.com/system-data
- Python Pandas to change the datatype fo the "tripduration" field
- Analytic tool Tableau Public for visualization


## Analysis and Results

1. A line graph displaying the number of bikes checked out by duration for all users, and the graph can be filtered by the hour 

[Checkout Times for Users](https://public.tableau.com/app/profile/falguni.mittal/viz/CheckoutTimesforUsers_16422946254300/CheckoutTimesforUsers)

2. A line graph displaying the number of bikes that are checked out by duration for each gender by the hour, and the graph can be filtered by the hour and gender 

[Checkout Times by Gender](https://public.tableau.com/app/profile/falguni.mittal/viz/CheckoutTimesbyGender_16422944910530/CheckoutTimesbyGender)

3. A heatmap showing the number of bike trips for each hour of each day of the week (10 pt)

[Trips by Weekday per Hour](https://public.tableau.com/app/profile/falguni.mittal/viz/TripsbyWeekdayperHour_16423528667100/TripsbyWeekdayperHour)

4. A heatmap showing the number of bike trips by gender for each hour of each day of the week, and the heatmap can be filtered by gender 

[Trips by Gender](https://public.tableau.com/app/profile/falguni.mittal/viz/TripsbyGenderWeekdayperHour_16423543703520/TripsbyGenderWeekdayperHour)

5. A heatmap showing the number of bike trips for each type of user and gender for each day of the week, and you can only filter by user and gender 

[User Trips by Gender by Weekday](https://public.tableau.com/app/profile/falguni.mittal/viz/UserTripsbyGenderbyWeekday_16423541450530/UserTripsbyGenderbyWeekday)

6. Bike Repairs

[Bike Repairs](https://public.tableau.com/app/profile/falguni.mittal/viz/BikeRepairs_16423652398710/BikeRepairs?publish=yes)

7. Bike Utlization

[Bike Utilization](https://public.tableau.com/app/profile/falguni.mittal/viz/BikeUtilization_16423652898150/BikeUtiization)

Story

[NYC Bike-share story](https://public.tableau.com/app/profile/falguni.mittal/viz/NYCBike-sharestory/NYCBike-sharestory?publish=yes)


### Outcomes:
- Checkout times for users: Most users checked out the bikes for less than 20 minutes.  No users checked the bike for more than 1 hour.
- Checkout times by Gender: Significantly more Males checked out the bike than the Females, but neither checked the bikes out for more than an hour.
- Trips by Gender: Male utilized the bikes more than Females. Both Males and Females had more trips from Monday through Friday.  Both Males and Females had more trips from 7:00AM to 9:00 AM and from 5:00PM to 7:00 PM
- Trips by Weekday per Hour: Peak hours are from 7:--AM to 9:00 AM  And from 5:00PM through 7:00PM from Monday through Friday. On Sat peak hours are from 11:00 am to 5:00PM .  and on Sunday from 10:00AM to 1:00PM
- User Trips by Gender: Male Subscribers had more trips than Female Subscribers. Both Male and Female Subscribers had more trips than Customers

Summary:

Per NYC Bike Share program, we expect more Males to participate in this program than Females and more Subscribers are expect to participate than Customers. The peak times on weekdays will be in the morning from 7:00AM - 9:00AM and in the evening fom 5:00PM - 7:00PM. Younger population is expected to ride for longer time.

Additional Suggested Visualizations:
- Starting Location by Gender
- Starting Location by Age
- Starting Locations for bikes with longest trips
- Average age of user type (Subscriber or Customer) 
- 