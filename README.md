# Automatic Billing System
### Description

*An **automatic billing system** for providing an ease to the customers while shopping and reducing the manual labour of the supermarkets.*

*The main motive behind introducing this technology is increasing the sales and providing positive feedbacks and preventing people from crowd and saving lots of time.*

### Table of Contents

- Requirements
- Technology Used
- Installation
- Working
- Team Members
- References

### Requirements

-	It requires a system through which user can interact with the machine.
-	A barcode scanner.
-	A screen
-	Internet.
-	Payment system
-	A security tag/sticker remover
-	Database of products

### Technology Used
#### Real System
  - Operating System (Windows, Linux or any other)
  - HTML , CSS , BootStrap for frontened
  - JavaScript Nodejs for backened
  - MongoDB for database
  - Scandit Barcode Scanner SDK for connecting and collecting information from barcode

#### App
  - Flutter for frontened
  - Firebase for backened
  
  
  

### Installation
#### Real System
  - The system needs a server to be hosted. We would be using AWS server for this.
  - The system needs to have a browser installed and proper internet connection

#### App
  - The user need to install the app provided.

### Working

1.	System will be displaying various advertisements, like offers running, upcoming offers, about other places associated with that market(restaurants, theatres, hotels, cafe) and a START button.
    (The wep application(HTML, CSS, Bootstrap) will show short videos and advertisements.)

2.	User clicks on start to start billing.

3.	It asks user to scan the product (visual & voice instruction)
4.	User scans the product using camera/barcode scanner (Scandit api will fetch the detail and provide to web application in javascript).
5.	All the details (product code, quantity, colour, price) of the product displays on the screen. (Based on the product code fetched from barcode, all the information from database will be taken and displayed over the scree). 
    Recommendations are displayed at bottom (Using ML and previous billing history the system will display the appropriate products which customer can prefer to buy). 
    A cart and a bill is displayed which keeps track of selected items and user has choice to remove and the bill and cart status updates with that.
6.	User finishes the billing by clicking on END. 
7.	Payment options displays on screen (UPI, Debit card, credit card, cash).
8.	In case of cash sends a notification to the staff to collect cash.
9.	If less amount paid then payment denies and asks again to pay else finishes this step.
10.	 Displays a message to remove security tags by using another system present.
11.	A camera will monitor and scan the product barcode while removing the security tag and matches the product code with the bill. If payment is not made then codes do not match and warning is generated (any suspicious action found).
12.	Security tags (RFID) of all the products on the bill will be deactivated successfully and process finishes.
13.	During checkout security system detects if any tags not removed and alarm beeps otherwise successful checkout.

### Team Members
- Abhishek Yadav
- Pawan Kushwaha
- Nikhil Shukla 
- Priyanka Rai

### References
- 
