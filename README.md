# TroweProject
Screenshots of the Database UI tool created at T. Rowe Price Summer 2018


  These images are screenshots of the database tool I created at my T. Rowe Price Internship summer 2018. This tool was created using Nodejs, JQuery, JQueryUI, Bootstrap, Javascript, HTML, CSS and the Amazon Web Service Tool, dynamo DB. 
  
  This tool helped the T. Rowe Call center team set and view when each of their different call centers were open.
The basic hours of operation data was dynamically pulled through a request to the AWS DynamoDB table and placed into the table on the webpage. Here, the data could be edited or deleted and then resubmitted, updating the table in the AWS cloud. 
 
 Another part of this project was managing the different call centers in the table. Because each call center had different hours, a dropdown menu was created that allowed users to view or delete current call centers or make an entirely new call center. Once again, when the data was submitted, the DynamoDB table would reflect these new additions or deletions in this web application's table.
