# Rain-Alert-app
## The objective of this project is to create a program to get a message to our phone to take our umbrella if it will rain in next 12 hours.
### Step 1: import the required modules(requests, os, twilio)
### Step 2: Get API for weather data .(i used data from openweathermap.org)
### Step 3: From the API data filter the data for weather for next 12 hours from hourly data.
### Step 4: Find if there is any id which is less than 600(we can find if it will rain by finding out the id which is less than 600)
### Step 5: If its rain use twilio to send a messege to my phone number about it.
### Step 6: use environment variables to hide the data that need to be secured.
### Step 7: upload the data to cloud to run it in a regular period of time.(i used pythonanywhere.com)
