# PWA-Text-Editor

## Description:

This application is a single-page application that is a PWA (Progressive Web Application), meaning that it will function offline if necessary. This app features data persistence techniques that serve as redundancy in case one of the options is not supported by the browser.

The functionality of this application will be accessible via a link to the deployed app on Heroku as requested by the assignment's Grading Requirements.

The assignment's User Story and Acceptance Criteria can be found in their own sections below.

## User Story:

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria:

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
Mock-Up
```

## Screenshots:
Here are a couple of screenshot of the main page of the app when deployed in Heroku:

![image](https://user-images.githubusercontent.com/112277445/223842647-5f9784b4-23de-4473-9b19-e282fc8a53c4.png)

![image](https://user-images.githubusercontent.com/112277445/223844632-f4b46075-7841-41e3-9576-36fece2bc64b.png)

This screenshot demonstrates the alert that pops up when you click "Install":

![image](https://user-images.githubusercontent.com/112277445/223844977-2ee8135d-9fa3-450f-bbab-fb967c9e0eef.png)

And finally, here is a screenshot of the installed app!

![image](https://user-images.githubusercontent.com/112277445/223845524-5cc2f839-88db-4d48-893a-60ecff21c066.png)

## Deployment Links:

Here is a link to my GitHub [repo!](https://github.com/roldanmoncada/pwa-text-editor)

Here is the link to the Heroku [deployed app!](https://pwa-text-editor-heroku.herokuapp.com/)