# Text Editor Starter Code

##  Table of Contents
- [Description](#description)
- [Overview](#overview)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshot](#screenshot)
- [Contributing](#contributing)
- [Questions](#questions)
- [License](#screenshot)
- [Credits](#credits)

##  Description
TextX is a cutting-edge text editor application designed to showcase your impressive skills and knowledge gained throughout your course. This app stands out with its exceptional implementation of concepts, delivering a powerful and feature-rich experience.

As a single-page application that meets the Progressive Web App (PWA) criteria, TextX offers seamless usability directly within the user's web browser. This eliminates the need for additional downloads or installations, making it easily accessible to potential employers and users alike.

One of the standout features of TextX is its robust data persistence techniques, ensuring the safety and availability of user data at all times. The application utilizes multiple redundancy options, so even if a browser does not support a particular technique, data integrity is maintained. Additionally, TextX operates flawlessly even when the user is offline, enabling uninterrupted productivity and editing capabilities.
With Team Profile Generator, managers can effortlessly generate visually appealing and informative team rosters. The app allows managers to enter the team manager's details, such as their name, employee ID, email address, and office number. It then presents a user-friendly menu to add engineers or interns or to finish building the team. By providing essential information like email addresses and GitHub profiles, Team Profile Generator ensures quick access to team member details. Furthermore, clicking on an email address automatically opens the default email program, while clicking on a GitHub username opens the respective profile in a new tab for seamless collaboration. Once the team is finalized, the application generates an HTML webpage, presenting a beautifully formatted team summary.

Experience the convenience and efficiency of Team Profile Generator, the ultimate tool for effortlessly creating detailed team summaries. Simplify your team management process and save valuable time by generating comprehensive team profiles with this intuitive command-line application.

##  Overview
### The Challenge
Build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.

### User Story
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use

### Acceptance Criteria
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

##  Technologies
* HTML
* CSS
* JavaScript
* Node.js
* Express.js
* Webpack
* Workbox
  
##  Installation
* Run npm I to install dependencies.
* Run npm run in the terminal to begin the program.
*  Go to http://localhost:3333/ to run the application locally
  
##  Usage
The application is deployed with Heroku. Please go to [Text Editor](https://pwa-texteditor-v2-427e1e7f4e91.herokuapp.com/)

##  Screenshot
![image](https://github.com/koshea1124/Text-Editor/assets/119077249/f7fb1ff1-b7cc-4710-98b8-b42570072c22)
![image](https://github.com/koshea1124/Text-Editor/assets/119077249/f187a310-7d64-4f13-a043-f74d1f4e2bd7)

##  Contributing
Please reach out via email or thru GitHub if you have any suggestions for imporovement

##  Questions
Please feel free to reach out if you have any questions:
* GitHub UserName: https://github.com/koshea1124
* Email: koshea1980@gmail.com

##  License
N/A

##  Credits
* [NPM Install](https://docs.npmjs.com/cli/v6/commands/npm-init)
* [Webpack](https://webpack.js.org/)
* [Workbox](https://developer.chrome.com/docs/workbox/reference/workbox-webpack-plugin/#type-GenerateSW)
* [NPM Inquirer](https://www.npmjs.com/package/inquirer)
* [Code Academy](https://www.codecademy.com/catalog)
* [Markdown Crash Course Video](https://www.youtube.com/watch?v=HUBNt18RFbo)
* [MDN Docs](https://developer.mozilla.org/en-US/)
* [Jest](https://jestjs.io/docs/getting-started)
