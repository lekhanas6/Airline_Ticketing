# Airline_Ticketing

Airline ticketing project report:

Process Description:
Business process involves various interrelated tasks from passengers initiating their flight booking process to receiving their ticket.
Throughout the process, the passenger goes through various steps for purchasing the tickets based on their needs. The process through which the passenger transverses through the funnel is primarily dependent on the decision of the passenger and the availability of the tickets.

Below are the interrelated tasks associated with the process:

●	A passenger will initiate the airline ticket booking by feeding the search fields according to their requirement. 

●	The ticket search engine will run the search engine and display the results.

●	The passenger will then select the airline and the flight according to their requirements.

●	The airline enquiry reception will check and confirm the flight availability and check for the seat availability

●	If the seats are available, the payment is initiated by the payment desk and the transaction is completed.

●	Airline ticket issue desk will receive the payment details and generate the air ticket which is then sent to the passenger.

Triggering event:
The trigger event here is the passenger purchasing the air ticket. 

Specific Result:
The passenger goes through the whole airline ticket booking process defined above to make the ticket purchase.

Customer:
The customer is the end user (passenger) who would be purchasing the ticket. 

Scope for improvement and actions are taken to enhance the process:
We've discovered that there's chance to increase process efficiency, which could have an impact on the company's bigger commercial objectives. We've discovered that purchasing plane tickets from several sellers can result in a loss of profit for both the airline and the client. As a result, we came up with an idea to lessen the danger of ordering tickets through third-party vendors by allowing clients to book their own tickets in a few simple steps and at a higher discount. Booking a ticket through a third-party vendor can cause significant delays and, in some cases, communication problems between customers and the airline operator. To resolve all of these issues, customers should contact the airline directly. Between the clients and us, we terminated the third-party vendors.
Furthermore, we discovered that linking clients directly with the airline firm eliminates any possibility of data breach i.e. compromise of personal information and financial details to unauthorized users. We've changed the process so that customers can cancel their own tickets at any moment before the departure date and receive a refund immediately to their bank account in a short period of time. Enhancing the procedure would improve data encryption and potentially create substantial revenues for the airline firm, with passengers receiving savings on trip tickets in return.

How did we improve the process and the impact of the change?
By eliminating third-party providers and linking customers and airline companies directly, we were able to streamline the process effectively.

Swim-lane diagram
As-is
Actors:
●	Passengers
●	Ticket search engine
●	Airline enquiry reception
●	Airline payment desk
●	Ticket issue desk

![Swim_lane_diagram](https://github.com/lekhanas6/Airline_Ticketing/blob/448dd144f5be66cdaea7e73f11533bb65dd1b01e/Swim_lane.png)

  
Possible outcomes with the process
1.	Can know the most preferred airline by the number of trips booked.
2.	Can know the search results those yielded a successful booking ticket.

Possible reports and visualizations from the database those which help airlines:
1.)	From booked tickets and passenger lists, for each method of payment, Airline can plan to offer corresponding incentives/rewards to the passengers. We can create an SQL query to identify list of passengers based on their method of payment. The report can then be used for predicting the lift curve for an incentive program on credit card users.

2.)	We can create a query to identify the longest flight and its price. Different airlines might have different pricings for a similar duration of flight. With this result, we can predict a tentative price an airline can aim for a future new flight between new destinations with similar flight durations.

3.)	We can create a SQL query to know most flown/preferred airline from the ticket booking history and passenger list. The query can help to know which airline needs improvements in attracting the passengers. 

4.)	We can create a SQL query to identify trip search results those which yielded a successful ticket booking. This powerful search helps to determine the high demand routes for airlines. Those searches which did not result in a ticket booking can be determined as low demand routes by the airlines.
