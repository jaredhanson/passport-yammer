# Welcome! 

To get this example working on your machine. 

## Install the dependencies

    npm install

## Create your Yammer app credentials

Go to the yammer site [https://www.yammer.com/client_applications](https://www.yammer.com/client_applications) and create an app to get a client id and secret key. 

## Fill in the credentials in app.js

      // Inside app.js
    7 var YAMMER_CONSUMER_KEY = "--insert-yammer-consumer-key-here--"
    8 var YAMMER_CONSUMER_SECRET = "--insert-yammer-consumer-secret-here--";

## Run the app

    node app.js