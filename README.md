# Captone-Project---Hotel-Booking-Analysis
Hotel-Booking-Analysis Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions! This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. Dataset Specs Count of rows= 119390 Count of columns= 32 Programming Language Python
IDE Google Colaboratory
Nomenclature Naming our dataframe is very crutial for any data analysis project as you have to call the dataframe time and again for every set of operation which are to be performed for the in-depth analysis.
In this case, our copy of the dataframe will be called 'df' , simple and easy to recall.
our data set contains booking information for a city hotel and resort hotel includes information such asd when the booking was made. length of stay, the number of adults. children and babies, and the number of available parking spaces, also other things all personally iddentifying information has from the data
we will perform exploratory data analysis with python to get insight from the data.
Data Variables Glossary hotel Two hotels are given: Resort Hotel City Hotel
is_canceled 1: Canceled 0: Not canceled cancelation 0 as not_canceled 1 as canceled df_not_canceled_guests dataframe with just not_canceled bookings lead_time gap between booking and arrival arrival_date_year arrival year arrival_date_month arrival month arrival_date_week_number arrival week arrival_date_day_of_month arrival date stays_in_weekend_nights count of nights the guests booked the hotel during Sat-Sun stays_in_week_nights count of nights the guests booked the hotel during Mon-Fri total_stay_nights duration of stay including weekend nights and week nights stay adults count of adults children count of children babies count of babies meal meal type (no meal package; BB; HB; FB) country country of guests df_country_guests_top10 top10 countries with most visitors market_segment TA: Travel agents TO: Tour operators distribution_channel is_repeated_guest 1: Yes 0: No previous_cancellations count of previous bookings that were cancelled by the customer before final booking previous_bookings_not_canceled count of no canceled bookings reserved_room_type booked room category assigned_room_type assigned room category booking_changes count of changes made by the customer before final booking deposit_type type of deposit made by the customer agent travel agent id company booking company id days_in_waiting_list count of days the booking was in the waiting list before it was confirmed customer_type Transient Contract Group Transient-party adr average daily rate for the booking price total price spent by a guest entity required_car_parking_spaces count of car parking spaces alloted by the customer total_of_special_requests count of special requests made by the customer reservation_status status of reservation reservation_status_date date corresponding to status of reservation 
Our analysis, would be capable of helping prospective guests in choosing the right hotel, right stay duration and much more for their stay and moreover, would also be introspecting for hotel management in bringing out changes (if, any) in their services for the guests.

SUMMARY OF CONCLUSIONS 
From the above analysis we can conclude that.

* The city hotels are doing more business that the Resort hotels as the booking percentage for city hotels are more than 60%
*The cancellation percentage is almost 27% and more than 72% booking were confirmed.
*More than double bookings were made in 2016. compared to the previous year. But the bookings decreased by 10-15%cnext year.
*Most bookings were made from july to august and the least bookings were made at the start and end of the year.
*Portugal, UK and France, Spain and Germany are the top countries from where most guests come, more than 80% come from these 5 countries.
*There are very low percentage of repeated guests coming to the hotels.
*Most people stay for one, two,three or four nights.
*The city hotels have more stay durations upto 5 nights whereas for the Resort hotels the most popular stay duration is one, two and seven day respectively.
*Most prefered meal type BB that is breakfast in the room. Very less percent of customers opt for FB which is the full boarding.
*The high percentage of bookings are coming from online TA(Travel Agent) section'
*The cancellation posibility increased with the increse of lead time.
*City hotel is ahead of Resort hotel in term of the Revenue as the booking ratio is higher.
*The maximum number of special request is coming for one time only.
*Couple (or 2 adults) is the most popular accommodation type. So hotel can make arragement plans accordingly.
*The lead time is possitively correlated to the total stay. that means the more the stay of the tourist the more the lead time will be'
*The adr and the number of guests are highly correlated means higher number of ghuests will result higher revenue.  
