# reverse-engineering

# DEBRIEFING
A simplistic security measure done by all user maintaining platforms in which is being initated & let's the user login & out safely.


# APPLICATIONS

-NodeJS

-MySql

-Express

-Sequalize


# GETTING STARTED TUTORIAL
To begin using this app clone this repository into your local storage. Once this is complete, do the following steps:

1) Create a mysql db called "passport_demo" 
2) Go into the config file, open config.js and insert your personal data; username and password.
3) Open a terminal in the repo and run "npm i" to install all node packages.
4) In the terminal run "node server.js" to connect to the server,
5) Open the browser and type "http://localhost:8080" in search bar.
6) You then sign-up and log in.

# Each File & What Each Job It Has

Most Important Files From Beginning To End In File Order

Authenticated.js - Stops any user from using it's platform unless it's logged in

config.json - A JSON file that holds components to connect to the server

passport.js - Let's the server know that the user needs an email & password

index.js - transfers data to & back to the database

user.js - An important factor of the security measures that adds a layer to protection regardly strictly the user & let's the database what is being stored

api-routes.js - a route that specifies what is to be shown client based wise

html-routes.js - let's the server know if the user signed in or already has an account

package.json - a file that usually contains all node modules

server.js - sets up the PORT, Express, & allows synchronization with the database while confirming a successful connection
------------------------------------------------------------