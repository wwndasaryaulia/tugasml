# Hotel booking demand
From the paper: hotel booking demand datasets

## About Dataset
Context

Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests?

This hotel booking dataset can help you explore those questions!

## Content

This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things.

All personally identifying information has been removed from the data.

## Acknowledgements
The data is originally from the article Hotel Booking Demand Datasets, written by Nuno Antonio, Ana Almeida, and Luis Nunes for Data in Brief, Volume 22, February 2019.

https://www.sciencedirect.com/science/article/pii/S2352340918315191

The data was downloaded and cleaned by Thomas Mock and Antoine Bichat for #TidyTuesday during the week of February 11th, 2020.

## Inspiration
This data set is ideal for anyone looking to practice their exploratory data analysis (EDA) or get started in building predictive models!

If you're looking for inspiration on data visualizations, check out the #TidyTuesday program, a free, weekly online event that encourages participants to create and share their code and visualizations for a given data set on Twitter.

If you'd like to dive into predictive modeling, Julia Silge has an accessible and fantastic walk-through which highlights the tidymodels R package.

## Data Description

    hotel: This attribute represents the type of hotel where the booking was made. It has two categories: "City Hotel" and "Resort Hotel," indicating whether the booking was for a city hotel or a resort hotel.

    is_canceled: This binary attribute indicates whether the booking was canceled (1 for canceled, 0 for not canceled). It is a crucial feature for understanding booking cancellation patterns.

    lead_time: The number of days between the booking date and the arrival date. This feature provides insight into how far in advance guests typically make their reservations.

    stays_in_weekend_nights and stays_in_week_nights: These two attributes represent the number of weekend nights (Friday and Saturday) and weeknights (Sunday through Thursday) the guest plans to stay in the hotel, respectively. They help in analyzing the length of the stay.

    adults, children, and babies: These attributes indicate the number of adults, children, and babies included in the booking. They are essential for understanding the composition of guests.

    meal: This attribute represents the type of meal package booked by the guest, such as "BB" (Bed & Breakfast), "HB" (Half Board), "SC" (Self Catering), "Undefined," or "FB" (Full Board).

    country: The country of origin of the guest. It provides information about the geographical distribution of guests.

    market_segment: This attribute represents the market segment associated with the booking, such as "Online TA" (Travel Agents), "Offline TA/TO" (Travel Agents/Tour Operators), "Groups," "Direct," "Corporate," "Complementary," or "Aviation."

    distribution_channel: This attribute indicates the distribution channel used to make the booking, including "TA/TO" (Travel Agents/Tour Operators), "Direct," "Corporate," "GDS" (Global Distribution System), or "Undefined."

    is_repeated_guest: A binary attribute indicating whether the guest is a repeated guest (1 for repeated guest, 0 for not).

    previous_cancellations and previous_bookings_not_canceled: These attributes represent the number of previous cancellations and previous bookings that were not canceled by the guest, respectively.

    reserved_room_type and assigned_room_type: These attributes specify the type of room reserved by the guest and the type of room assigned to the guest, respectively.

    booking_changes: The number of changes or modifications made to the booking. It reflects how often guests modify their reservations.

    deposit_type: This attribute indicates the type of deposit made for the booking and can be "No Deposit," "Non Refund," or "Refundable."

    days_in_waiting_list: The number of days the booking was on the waiting list before it was confirmed.

    customer_type: This attribute represents the type of customer, such as "Transient," "Transient-Party," "Contract," or "Group."

    adr: Average Daily Rate, which is the average price per night of the booking.

    required_car_parking_spaces: Indicates the number of car parking spaces required by the guest.

    total_of_special_requests: The total number of special requests made by the guest.

    reservation_status: The reservation status, which can be "Check-Out," "Canceled," or "No-Show."

    reservation_status_date: The date when the reservation status was last updated.

    arrival_date: The date of guest arrival.
