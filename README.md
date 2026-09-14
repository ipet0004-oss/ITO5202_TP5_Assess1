# ITO5202_TP5_Assess1
Assessment 1: Analysing historical data with system performance - Phase 2

Student ID: 35723483
Unit Code: ITO5202
Teaching Period: 5, 2026
Dataset: Uber Data Analytics Dashboard (https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link/data)



Column name	Description	Data Type
Date	Date of the booking	Date and Time (temporal)
Time	Time of the booking	Date and Time (temporal)
Booking ID	Unique identifier for each ride booking “CNR#######”	String
Booking Status	Status of booking (Completed, Cancelled by Customer, Cancelled by Driver, etc.)	String (categorical)
Customer ID	Unique identifier for customers “CID#######”	String
Vehicle Type	Type of vehicle (Go Mini, Go Sedan, Auto, eBike/Bike, UberXL, Premier Sedan)	String (categorical)
Pickup Location	Starting location of the ride	String
Drop Location	Destination location of the ride	String
Avg VTAT	Average time for driver to reach pickup location (in minutes)	Float
Avg CTAT	Average trip duration from pickup to destination (in minutes)	Float
Cancelled Rides by Customer	Customer-initiated cancellation flag	Integer (categorical - 1 or null)
Reason for cancelling by Customer	Reason for customer cancellation	String (free text)
Cancelled Rides by Driver	Driver-initiated cancellation flag	Integer (categorical - 1 or null)
Driver Cancellation Reason	Reason for driver cancellation	String (free text)
Incomplete Rides	Incomplete ride flag	Integer (categorical - 1 or null)
Incomplete Rides Reason	Reason for incomplete rides	String (free text)
Booking Value	Total fare amount for the ride	Integer
Ride Distance	Distance covered during the ride (in km)	Float
Driver Ratings	Rating given to driver (1-5 scale)	Float (categorical null, 1-5)
Customer Rating	Rating given by customer (1-5 scale)	Float (categorical null, 1-5)
Payment Method	Method used for payment (UPI, Cash, Credit Card, Uber Wallet, Debit Card)	String (categorical)

