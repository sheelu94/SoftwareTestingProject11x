Test plan : Appointment Booking API
1.	Objective :  
      To validate the functionality of the booking API at https://katalon-demo-   cura.herokuapp.com/  that allows users to -
•	Log in with valid credentials 
•	Book an Appointment with specified details 
•	Log out of the session

2.	Scope :    
This test plan covers
	Authentication of the user using the login API 
	Creating the appointment using the make appointment API
	Logout Functionality

                
3.	Test Environment :  
•	Base URL :  https://katalon-demo-cura.herokuapp.com/
•	Tools :  Postman  / Jmeter / Automation with Rest Assured ( java).
•	Auth Type : None
•	Content Type : 


4.	API EndPoints : 
4.1	. Login API – 
URL-  https://katalon-democura.herokuapp.com/authenticate.php
Method – Post
Header – 
Payload – plaintext 
CopyEdit 
username=John Doe 
password=ThisIsNotAPassword
Authentication – None
Response validation – 
Status code- 200
Response Body – should indicate success or failure 
Token or session validation – 

4.2	. Make Appointment API – 
•	URL- https://katalon-demo-cura.herokuapp.com/authenticate.php 
•	Method- Post
•	Header-
•	Payload- 
•	Authentication- none
•	Response Validation – 
     Status code- 200
     Response Body – Should confirm appointment details eg- appointment ID and confirmation message . 

5.	Test Scenarios- 
Positive Test cases- 
•	TC01: Valid Login – Expect success and session initiation. 
•	TC02: Valid Appointment – Submit required fields, expect confirmation. 
•	TC03: Try Multiple Facilities – All valid entries should succeed. 
•	TC04: Valid Date Format – Standard DD/MM/YYYY should work. 
•	TC05: Valid Logout – Expect session termination and redirection.
      Negative test cases- 
•	TC06: Invalid Login – Wrong credentials should return an error.
•	TC07: Missing Login Fields – Empty username/password returns error. 
•	TC08: Missing Appointment Fields – Should return validation error. 
•	TC09: Invalid Date Format – e.g., 2024-25-09 should fail. 
•	TC10: Unauthorized Appointment Request – Should fail without login. 
•	TC11: Logout Without Session – Should redirect or show default behavior.



6.	Test Data-
Valid Credentials 
•	Username- John Doe
•	Password- ThisIsNotAPassword
Facility-   
•	Seoul CURA Healthcare Center 
•	Tokyo CURA Healthcare Center
Visited Dates- 
•	Valid- 25/11//2024
•	Invalid- 2024-09-25, 99/9





7.	Notes & Assumptions 
• JSON is used for both login and appointment creation requests. 
• Logout is a simple GET request that triggers session termination. 
• No tokens or headers are explicitly required unless session-based handling via 
cookies is necessary. 
1.	• Response structure and session handling should be confirmed during testing.


8.	Risks & Assumptions 
•	API URL for appointment and login is currently the same — may be a typo or misconfiguration. 
•	No authorization mechanism implemented yet (Auth: NO) 
•	 Assuming appointments do not require login/session as per current setup




9.	Test Deliverables 
• Postman Collection / JMeter Script 
• API Test Report with status of test cases 
• Bugs/Defects logged (if any)

