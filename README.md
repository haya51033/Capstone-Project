# Capstone-Project 
Stage 1

DSH for Travel and Turism


Description 

DSH offers the ability to display cities information and you can reserve hotels/flights online easily. You should charge a credit in your app account and then you can reserve your flight/hotel directlly and quickly (no nessessary to enter your credit card information in every time you do a reservation). Also you can do an offer reservation which that include a full packege of reservation (round flights and hotels reservation) with special offers.







Additional: DSH Use cases:
 
Intended User

DSH is intended for travelers who want an easy and fast way to do their reservations and want a best prices and offers

Features

•	DSH save your reservation locally which that mean you can display your confirmed reservation offline.
•	DSH Available in Arabic and English.
•	DSH use google map for hotel locations.
•	DSH provide easy way to call hotel by just click.
•	DSH support ads.
•	You can display the hotels rates and also you can add a rate for hotel.


Key Considerations

How will your app handle data persistence? 

DSH use SQLite database with content provider
Describe any edge or corner cases in the UX.
This is a simple flow chart describe the cases in the UX 


Describe any libraries you’ll be using and share your reasoning for including them.

•	DSH use Picasso library to display the Images, Picasso download the image and manages it.
•	DSH use Retrofit Library to fetch data from the server, this amazing library makes the life of the developer much easier, helping to manipulate threads.


Describe how you will implement Google Play Services or other external services.

•	DSH use google map for hotel locations. By using ApiKey from Google and add it to Manifest and add permissions:
1.	Android.prmission.INTERNET
2.	Android.permission.ACCESS_FINE_LOCATION
•	DSH support ads. Using ad id (I will use google ads).

Next Steps: Required Tasks

Task 1: Project Setup
•	Configure libraries: Picasso, Retrofit, GSON,…etc.
•	Build database and content providor.
•	Call the Api.

Task 2: Implement UI for Each Activity and Fragment

•	Build UI for Registration and other for Login.
•	Build UI for MainActivity (Home) for both (Registered user and Guest).
•	Build UI for The list of countries,Cities, Hotels.
•	Build UIs for compleate reservation (hotel, flight and offer).
•	Build UI for charge credit by adding credit card informations. (now I will not implement the code of real charge mony).
•	Build UI for display the confirmed reservations info.
•	Build UI for send message to the DSH support (contact us).

Task 3: Your Next Task

•	Adding navigation drawer layout to easy navigation between app services
•	Adding share button to share the DSH app experience with a friend.


