# main-app-with-micro-frontend

## Description

This is a helloworld main web app that embeds a [micro frontend](https://github.com/mapteb/web-component-micro-frontend) as a custom element. This main app (localhost:8080) raises a custom event 'my-custom-event' and the embeded micro frontend app (localhost:8081) receives it and echoes the event.detail.message content.  

## Usage

When built and deployed, this app displays a button which when clicked raises a custom event 'my-custom-event'. The embedded micro frontend receives the event and echoes the event.detail.message content. 


## Build and Run

Since this app has just one html file, it can be run directly like:

http-server << accessing http://localhost:8080 should display the button and the embedded micro frontend >>


## Screenshots

Wiki Page: [Screenshots](https://github.com/mapteb/main-app-with-micro-frontend/wiki/Screenshots)
