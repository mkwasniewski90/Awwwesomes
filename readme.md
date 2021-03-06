# Awwwesomes Summer Meetup - August 2017
An isomorphic and framework agnostic progressive web app demo that includes the Web App Manifest, Service Workers, Cache API and Push Notifications.

## Usage
- Run `npm install` to install all the required dependencies
- Run `npm install -g webpack` to install webpack globally on your machine.
- Run `npm run build` to build the project using webpack configurations.
- Run `npm start` to start a node server on `localhost:3000`

## Progressive Web Apps
“Progressive web apps are ordinary mobile-friendly web applications that may be progressively enhanced into native-like applications through the modern browser.”

### Mobile Friendly Applications
At it’s core, a PWA is little more than an ordinary website; composed of HTML, CSS & JavaScript.

### Progressive Enhancement
A website must be built in a structured-layered approach, with rock-solid HTML & content and enhancements added to improve the user’s experience.

### Native Features
The most exciting aspect of a PWA is definitely the native-like user experience and features. A progressive web app is able to work offline, receive push notifications and should be optimized to work flawlessly on mobile devices.

### App-Shell Model
The “app-shell” could be compared to the code you would publish to the app store if you were building a native app. Inspiration taken from [application-shell](https://github.com/GoogleChrome/application-shell).

### Service Worker
A service worker is a script that your browser runs in the background, separate from a web page, opening the door to features that don't need a web page or user interaction.

### Web App Manifest
A simple JSON file that must follow the specification available on [W3C](https://w3c.github.io/manifest/"), it is possible to run the web app in full-screen as a standalone application, assign an icon which will be displayed once the application is installed onto the device or assign a theme and background colour to your app. In addition, Chrome on Android also proactively suggests to the user to install the web app using [Web App install banners](https://developers.google.com/web/updates/2015/03/increasing-engagement-with-app-install-banners-in-chrome-for-android).

### Technology
Built using isomorphic JavaScript, running on ExpressJS on the server-side and native JavaScript on the client-side.
