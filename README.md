# Face-Recognition-WebApp

This is a tiny demo application which demonstrates the Amazon AWS 'Rekognition' face and image recognition API, as well as the 'Polly' speech synthesis API.

It uses the JPEG Camera library to take a photo from your PC/device onboard camera and send the facial data to Amazon for comparison and identification.

## Prerequisites

You will need Ruby installed on your development machine.
Before running this web app, you will need to set up a .env file in the project folder with your Amazon IAM key and secret which you can generate from the aws console.

```
export AWS_KEY=<your IAM key here>
export AWS_SECRET=<your IAM secret here>

Once that is done, you can install all dependencies by typing:

bundle install```

Then run the web app by typing:

ruby faceapp.rb```

This will start a local web server, listening on port 4567.  Then it is a matter of visiting the following URL in your web browser:

```
http://localhost:4567

