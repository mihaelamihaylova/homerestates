# Homerestates
Functional requirement specification

Here is a list of the functionalities that are implemented and are in need of testing. Anything that is not present in this section is considered out of scope and it shouldn’t be tested.

2.3.1.	    Use Case 1 (Accessing the system) 

The system is accessed through the internet from its initial URL. It loads all components of the home page.

2.3.2.	    Use Case 2 (Navigation bar)

2.3.2.1.	Navigation bar – Guest

Guest users have the following links on the navigation bar:

•	Home page - a small house icon
•	Blog
•	Login
•	Register

2.3.2.2.	Navigation bar – Registered user

Logged in users have the following links on the navigation bar:

•	Home page - a small house icon 
•	Sale
•	Rent
•	Add offer
•	My offers
•	Profile
•	Inquiries
•	About us
•	Blog
•	Logout

2.3.3.	    Use Case 3 (Home page)

The home page should consist of the following components:

•	Nav bar
•	Section 1 – Search for properties
o	Includes the following options:
	Sale
	Vacant lot
	City
	Max price
	Find property - button
•	Section 2 – Listed properties
•	Footer – It is out of scope and shouldn’t be tested

2.3.4.	    Use Case 4 (Offer details page)

This page provides a few components. The first half of the page consists of the picture of the property, its price and address. Second half on the left has two forms. 

The first form is used to make an inquiry for a certain offer. Fields with the respective error messages are:
•	First name
o	“First name must be between 3 and 20 characters”
•	Last name
o	“Last name must be between 3 and 20 characters”
•	Telephone number
o	“Phone number must have at least 7 digits”
•	Email
o	“Email cannot be blank”
•	Contact hours
o	“You must select contact hours!”
•	Message
o	“Message cannot be empty”

All of them are required. The form ends with a button – “Contact us”

Below it sits the comment form. It represents a text box with a button – “Add comment”. Above the textbox, there is a text – “Add a comment about the offer”.

On the right side of the forms, there is a detailed description of the properties. It is out of scope and you don’t need to check that information.

There is a comments section below the description. Its heading is “Comments”. Each comment has an owner name and a date and time of the comment, and the comment is inside a text box below.

2.3.5.	 Use Case 5 (Register page)

It consists of a registration form with the following fields:

•	Username – required
•	Full name – required
•	Email – optional
•	Address – optional
•	Password – required
•	Confirm password – required

Error messages are out of scope.

2.3.6.	 Use Case 6 (Login page)

Login page is very standard, it has two fields:

•	Username
•	Password

The error messages are displayed in a red box above the form. They are the following:

•	Non-existent user: “This username and password combination does not exist.”
•	Empty fields: “Please enter the required information in the fields.”
•	Empty username: “Please enter your username.”
•	Empty password: “Please enter your password.”

The form ends with a “Login” button.

2.3.7.	 Use Case 7 (My offers page)

The page is very simple. It contains a list of the offers that the user has created. It has a line with a heading “My offers”.

2.3.8.	 Use Case 8 (Edit profile page)

Edit profile page has a form for editing user information:

•	Username
•	Full name
•	Email
•	Password
•	Confirm password
The form ends with a button “Change”. Above the form there is a text: “Edit {username} information”.

2.3.9.	 Use Case 9 (Inquiries page)

The page is very simple. It contains a list of the offers that the user has sent an inquiry for. It has a line with a heading “Inquiries”.

