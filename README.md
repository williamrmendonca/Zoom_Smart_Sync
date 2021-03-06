[![forthebadge](https://forthebadge.com/images/badges/built-with-love.svg)](https://forthebadge.com)
[![forthebadge](https://forthebadge.com/images/badges/made-with-javascript.svg)](https://forthebadge.com)


# Zoom Smart Sync
Zoom Smart Sync is a desktop application built on Electron.JS which enables the files stored in the local system to be synced with AWS S3.

The features of Zoom Smart Sync can be stated as below:<br>
1. User has to login to use the application.<br>
2. Uploads files to S3 by drag & drop.<br>
3. Uploads files through background auto sync process.

<img src="Screenshots/login_screen.jpg" width="250" height="377" align="left"/> <img src="Screenshots/App_UI.jpg" width="500"/> 
 
## Installation

### Windows Installer
Install the given .exe file and use the application. The app's directory will be created on desktop.

### Build from scratch [Linux, Win, MacOS]

Prerequisite<br>
* NodeJS and NPM should be installed in the system.

API
1. Run ```npm install``` in api folder's terminal.
2. Run ```npm start``` to start the server.

APP
1. Run ```npm install``` in app folder's terminal.
2. Run ```npm start``` to start the server.

To build<br>
* Run ```npx electron-builder build``` in app folders's terminal.

## Built with

1. Node.JS
2. Electron.JS
