# login-application
As a fresher i don't have enough knowlegde to meet your expectation. 
But i still tried my best to complete this task. thanks to this assignment  i had learned new thinks like google firebase, and http.  

backend of a login application built uisng .net and mysql.
Steps to implement this project:


Step 1: Set up a Firebase account To use Google Firebase APIs to send OTPs, we need to set up a Firebase account and project. Follow these steps to set up a Firebase project:
1.	Go to the Firebase console (https://console.firebase.google.com/).
2.	Click on "Add project".
3.	Enter the project name and select the country/region for the project.
4.	Click on "Create project".
5.	After the project is created, click on "Authentication" from the left menu.
6.	Enable the "Phone" sign-in method and configure the phone number authentication settings.



Step 2: Set up .NET Core project
1.	Create a new .NET Core project in Visual Studio.
2.	Add the necessary NuGet packages such as FirebaseAdmin, MySql.Data.EntityFrameworkCore, and Microsoft.EntityFrameworkCore.Design.
3.	Create a Startup.cs file and configure the required services.


Step 3: Send OTP via Firebase API To send OTP via Firebase API, we need to use the Firebase Admin SDK. Follow these steps to send OTP via Firebase API:
1.	Create a Firebase project in the Firebase console.
2.	Install the FirebaseAdmin NuGet package in your .NET Core project.
3.	Get the Firebase Admin SDK configuration file and add it to your project.
4.	Initialize the Firebase Admin SDK with the configuration file.
5.	Call the FirebaseAdmin.Auth.FirebaseAuth.DefaultInstance.SendSignInLinkToPhoneNumberAsync() method to send the OTP to the user's phone number.


Step 4: Store phone number and OTP in database
1.	Create a MySQL database and table to store the phone number and OTP.
2.	Create a model class for the table and configure the entity framework to use MySQL.
3.	When the user successfully logs in, store the phone number and OTP in the database.


Step 5: Validate OTP via API
1.	Create an API controller to handle OTP validation requests.
2.	Get the phone number and OTP from the request body.
3.	Check if the phone number and OTP match the ones stored in the database.
4.	Return the result of the validation to the client.
Note: As I am an AI language model, I cannot provide the detailed code files and images for this application. However, I hope this guidance helps you in building the login application as per your requirements.

