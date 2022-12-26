# Hotel-booking-analysis-EDA-
Analyzing The Data of Hotel Booking(EDA-capstone project)


![image](https://user-images.githubusercontent.com/92503896/209557546-25d198c0-4dfa-46ed-a573-172b7a3377f4.png)


## **Introduction:**

Have you ever wondered the trends for hotel bookings? How long a
person stays? How often people cancel? What the busiest months
are? In this analysis I explore a large dataset to examine these
questions.

The data contains “booking due to arrive between the 1st of July of
2015 and the 31st of august 2017”. This dataset contains information
on records for client stays at hotels. More specifically, it contains
booking information for a city hotel and a resort hotel, and includes
information such as when the booking was made, length of stay, the
number of adults, children, and/or babies, and the number of
available parking spaces, among other things. For the purpose of this
post, I only focused on some of the important variables to examine.

## **Problem Statement:**

The main objective of this project is to explore and visualize the
dataset from hotel booking data using basic exploratory data
analysis techniques. This will be done by finding out the
information such as when the booking was made, length of stay,
the number of adults, children, and/or babies, and the number of
repeated guests, among other things.

## **Feature Description:**

The dataset has around 119390 observations in it with 32 columns
and it is mix between categorical and numerical values

* Hotel
○ Resort hotel

○ City hotel
* is_canceled
○ 1: Cancelled
○ 0: Not cancelled
* lead_time
○ No of days that elapsed between entering date of booking
into property management system and arrival date

* arrival_date_year
○ Year of arrival date (2015-2017)
* arrival_date_month
○ Month of arrival date (Jan - Dec)

* arrival_date_week_numberr
○ Week number of year for arrival date (1-53)
* arrival_date_day_of_month
○ Day of arrival date
* stays_in_weekend_nights
○ No of weekend nights (Sat/Sun) the guest stayed or
booked to stay at the hotel

* stays_in_week_nights
○ No of week nights (Mon - Fri) the guest stayed or booked
to stay at the hotel

* Adults
* Children
* Babies
* meal
○ Type of meal booked. Undefined/SC – no meal package;
○ BB – Bed & Breakfast;

○ HB – Half board (breakfast and one other meal – usually
dinner);
○ FB – Full board (breakfast, lunch and dinner)
* country
* market_segment (a group of people who share one or more
common characteristics, lumped together for marketing
purposes)
○ TA: Travel agents
○ TO: Tour operators
* distribution_channel (A distribution channel is a chain of
businesses or intermediaries through which a good or service
passes until it reaches the final buyer or the end consumer)
○ TA: Travel agents
○ TO: Tour operators
* is_repeated_guest (value indicating if the booking name was
from repeated guest)
○ 1: Yes
○ 0: No

* previous_cancellations
○ Number of previous bookings that were cancelled by the
customer prior to the current booking

* previous_bookings_not_canceled
○ Number of previous bookings not cancelled by the
customer prior to the current booking

* reserved_room_type
○ Code of room type reserved. Code is presented instead of
designation for anonymity reasons.

* assigned_room_type

○ Code for the type of room assigned to the booking.
Sometimes the assigned room type differs from the
reserved room type due to hotel operation reasons (e.g.,
overbooking) or by customer request. Code is presented
instead of designation for anonymity reasons.

* booking_changes
○ Number of changes/amendments made to the booking
from the moment the booking was entered on the PMS
until the moment of check-in or cancellation

* deposit_type
○ Indication on if the customer made a deposit to
guarantee the booking. This variable can assume three

categories: No Deposit – no deposit was made; Non-
Refund – a deposit was made in the value of the total stay

cost; Refundable – a deposit was made with a value under
the total cost of stay.

* agent -ID of the travel agency that made the booking
* company
○ ID of the company/entity that made the booking or
responsible for paying the booking.

* day_in_waiting_list
○ Number of days the booking was in the waiting list before
it was confirmed to the customer.

* customer_type:
○ Contract - when the booking has an allotment or other
type of contract associated to it;
○ Group – when the booking is associated to a group;

○ Transient – when the booking is not part of a group or
contract, and is not associated to other transient booking;
○ Transient-party – when the booking is transient, but is
associated to at least other transient booking

* adr (average daily rate)
* required_car_parking_spaces
○ Number of car parking spaces required by the customer
* total_of_special_requests
○ Number of special requests made by the customer (e.g.
twin bed or high floor)

* reservation_status
○ Cancelled – booking was cancelled by the customer;
○ Check-Out – customer has checked in but already
departed;
○ No-Show – customer did not check-in and did inform the
hotel of the reason why
* reservation_status_date
○ Date at which the last status was set.


## **Steps involved doing this project:-**

     Loading Data
     Load python libraries
     Load dataset
     Cleaning dataset
     Analyzing and Visualizing the Data
     
     
## **Conclusion:**

1. Majority of the hotels booked are city hotel.

2. Majority of the guests are from Western Europe.So target this area for more customers.

3. 2016 showed the highest rate of hotel bookings.(data from 2015-2017)

4. We should also target months between May to Aug.Those are peak months due to the summer period.

5. No deposit policies lead to a higher cancellation rates.

6. Since there are very few repeated guests,focus should be on retaining the customers after their first visit.

7. The majority of reservations convert into successful transactions.

8. More bookings occured on weekdays vs weekends.

9. Most bookings came from independent,transient customers.


