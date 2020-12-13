TwitchEventSub
Basic setup of Twitch's Event Sub notification system

Functionality
App Access Token Creation/Verification
Subscription Creation
Subscription Deletion
Subscription Notifications

Built With
Nodejs

Prerequisites
npm install 
nodejs
ngrok


Getting Started

Install Ngrok for Https on local machine
https://ngrok.com/
path to folder with ngrok.exe
Commandline: ngrok http localhost:3000
copy https url and past as callbackURL in project
example: https://41d23fb48362.ngrok.io

npm i

Update constants:
Enter your Twitch client credentials
const clientID = '<YOUR CLIENT ID>';
const clientSecret = '<YOUR CLIENT SECRET>';
const callbackURL = '<YOUR NGROK URL>';
broadcaster_id = '<CHANNEL ID>';

nodemon eventSub.js

Usage
Use this repo to subscribe your application to twitch event notifications for specific channels.
List of subscriptions available: https://dev.twitch.tv/docs/eventsub/eventsub-subscription-types

For more examples, please refer to the Documentation
https://dev.twitch.tv/docs/eventsub

Contact
James Waugh - @MrJwaugh3 on Twitter

Reference
https://dev.twitch.tv/docs