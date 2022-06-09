# SafeCity
![safecity4](https://user-images.githubusercontent.com/46609198/172941820-5bfb699a-9086-460c-bb91-67ccb2e3a7f9.PNG)
## Overview 
Welcome to SafeCity. Inside the file named "CODE" you will find all the code that is absolutely necessary to run the web app. 

This includes the following:
* index.html: Main file with most of the code used to generate a d3 interactive application for the user, this includes all the html and javascript of the app.
* index.css: All the css code that gives the main index file all the styling and colors. 
* data: a file that includes all the data necessary to run our application. Inside you will find updated_LA.json (used for main score calculations / visualization of neighborhoods) and allcrimes.csv (used mainly for crime visualization). 
* lib: d3 libraries used to create our application. 
Inside the DOC file you will find both the poster and final report as specified by the project requirements.

## Installation 
To install our application please execute the following steps:
1. First download and unzip the folder. 
2. Open your terminal and navigate to the folder named CODE inside the unzipped folder.
3. Once in it, run a local python server on port 8000 from the terminal. (How to do it: https://ryanblunden.com/create-a-http-server-with-one-command-thanks-to-python-29fcfdcd240e)
4. Once the server is initialized, open google chrome and go to the address: http://localhost:8000/
5. Let the visualization load, and enjoy!

## Execution 
To execute our application, follow the following steps:

1. Follow the installation process described above. 
2. Read welcome message on the sidebar.
3. Select your ideal weights for the type of crime and click on your desired neighborhood. 
4. Get your safety score for the selected neighborhood on the map. 
5. Zoom in on map for greater detail of each type of crime classified by color. 
