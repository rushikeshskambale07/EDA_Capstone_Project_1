### EDA_Capstone_Project_1

### HOTEL_BOOKING_ANALYSIS:
Exploratory data analysis Project of Hotel Booking Analysis:
This is exploratory data analysis project of hotel booking analysis which contain data set of hotel bookings, information about booking city, length of stay, booking channele, when booking was made, number of adults, number of children and babies, parkig spaces etc. We will perform exploratory analysis on this data set.

### Objective
Main Objective of the project is to maximize bookings, minimize cancellations and Maximise Customer retention as well as stay longevity.
 

### Data Set 
The file contain following features as column
1. hotel
2. is_cancled
3. lead_time 
4. arrival_date_year 
5. arrival_date_month
6. arrival_date_week_number
7. arrival_date_day_of_month
8. stays_in_weekend_nights
9. stays_in_weekend_nights
10. adults
11. children
12. babies
13. meal
14. country
15. market_segment
16. distribution_channel
17. is_repeated_guest
18. previous_cancellation
19. previous_bookngs_not_cancelled 
20. reserved_room_type
21. assigned_room_type
22. booking_changes
23. deposit_type
24. agent 
25. company
26. days_in_waiting_list 
27. customer_type
28. adr 
29. required_car_parking_space 
30. total_of_special_request
31. reservation_status
32. reservation_status_date 

### Tools and Libraries 
We used python as language and following Libraries of python
1. Numpy
2. Pandas
3. Matplotlib
4. Seaborne
5. Plotly
6. Folium

### Exploratory Analysis
Q1. Where do the guests come from? From which country most guests come?    
Q2. Which hotel type has more yearly bookings? 
Q3. Study Monthly arrival pattern of Guests?  
Q4. Which hotel type has more cancellations?  
Q5. How long do people stay at the hotels?  
Q6. Which meal type is most preferred meal of customer? 
Q7. What is the monthwise average daily rate (ADR)?
Q8. Which is the most reserved room type?
Q9. What is the most common customer type?
Q10. How does the price per night changes yearly?
Q11. How does the price per night varied on monthly basis?

### Conclusion 
1) Highest number of guests are from Portugal followed by Great Britain and France..Least number of visitors came from Countries like Zambia,Madagascar,Sychelles,Faroe Islands etc.Hence there is scope to increase footfall from these countries from where number of customers were less.
2) Bookings across years is higher for city hotel compared to resort hotel.
3) Monthly visit pattern shows a "wave like" pattern where months of July & August were heavily visited and November,December,January were least visted.Other months were moderately visited.
4) Around 40% bookings were cancelled in city hotel and 30% in resort hotel.
5) Duration of stay reduces drastically after week's stay for City hotels and reduces drastically after fortnight for resort hotels.Resort hotels seem to be visited for stays either on weekend or weekly or fortnighly basis. People use city hotels mostly for short stays(1-4days). Special customised Packages can be suggested to increase the stay duration.
6) Breakfast is most prferred mealtype followed by Breakfast+Dinner and Self catering. Therefore customer experience has to be taken specialy care during timings of these meals as well as availability of utensils, gas in kitchen or kitchenette where guests can prepare their own food.
7) For resort hotels, the average daily rate is more expensive during august, july and september. For city hotels, the average daily rate is more expensive during august, july, june and may.
8) The " A " room type is the most popular among the clients.
9) Transients are the most common customer type.
10) On the above line graph we can conclude that the city hotel continuously changes their night prices per year. While in resort hotel it has a falldown at year 2016 and then it also increases prices.
11)There is marked difference in maximum and monthly room price for resort hotels whereby room prices in busiest month of Aug is more than 6 times that of lean month of January. This difference is comparitvely very less for city hotels..

### Challenges 
1. The data contain to many null values 
2. There is also wrong data format in some columns like agent, children,companies etc.
3. cleaning of duplicate data 
4. choosing proper visualisation graph 
