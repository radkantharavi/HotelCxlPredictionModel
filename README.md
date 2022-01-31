# HotelCxlPredictionModel

Data Source- https://www.kaggle.com/jessemostipak/hotel-booking-demand

Target Variable- Is_Cancelled

Predictors Used- 'hotel','lead_time','total_of_special_requests','required_car_parking_spaces', 'booking_changes', 'previous_cancellations', 'is_repeated_guest','adults', 'previous_bookings_not_canceled','days_in_waiting_list', 'adr'.

AIM- Understand existing patterns around Hotel Bookings getting cancelled and build a predictive model to understand if a new booking is likely to cancelled/not and the factors impacting such an event as well. 

Metadata- https://www.sciencedirect.com/science/article/pii/S2352340918315191

Model Evaluation and Accuracy-

	**Model Name**	         **Accuracy**	**Run time**
	Random Forest	               0.80	      0.56
	Artificial Neural Network      0.77	      88.8
	KNN	                       0.76	      617.47
	Logistic Regression	       0.73	      7.16
	Decision Tree	               0.63	      0.42
