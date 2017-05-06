# Mini Chat Service
A web application for a chat system with really simple operations built using Angular 2, loopback and Socket.IO.

## Application Features
### As a visitor I can:
+ register with email, username, full name, password
+ login with username and password

### As a user I can:
+ View all users in the system
+ Get a notification whenever any user get online or offline
+ See online users and offline users
+ Send and receive a message from any user
+ See a history summary of my conversations
## Application Architecture
### Angular Front End
Angular project is structured to be easy extended.
To install the project you need nodejs at least 6.5 and npm
+ navigate to chat-service-frontend
+ open terminal in current directory
+ type "npm install" without quotes
Now it's installed to start the project type in the terminal "ng serve"

### Nodejs Back End
The nodejs project is built using loopback from Strongloop version 3.0
To install the project you need nodejs at least 6.5 and npm
+ navigate to chat-service-backend
+ open terminal in current directory
+ type "npm install" without quotes
Now it's installed to start the project type in the terminal "node ."
