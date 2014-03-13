# Live Twitter Heatmap

Streams Twitter public stream API through Node.js + Socket.io to Google's Maps V3 and makes a heatmap of the 400 most recent tweets (configure max in public/javascripts/main.js).

Makes use of the nite-overlay by https://github.com/rossengeorgiev as well, for prettiness.

Requires Twitter API key as well as access token (get them from https://apps.twitter.com/) set as environment variables (`consumer_key`, `consumer_secret`, `access_token_key`, `access_token_secret`)

## Installation

`npm install`

## Running

`node app.js`

Or just configure your environment variables on a Heroku app, enable WebSockets (`labs:enable websockets`) and run.