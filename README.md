# demo-cucumber
Create a directory 
Say demo

npm init --yes #package.json will get created automatically

code . # It will open VSCode editor with the root directory automatically

Add below dependancy in package.json below license:
"dependencies": {
    "chai": "^3.5.0",
    "cucumber": "^2.1.0",
    "grunt": "^1.0.1",
    "grunt-cli": "^1.2.0",
    "grunt-shell": "^2.1.0",
    "gulp": "^3.9.1",
    "gulp-shell": "^0.6.3"
  }
   
  npm install #It will create node-module folder and package.lock.json
  
  Add below scripts in package.json below main:
  
  # It will run on mac not sure about window 
   "scripts": {
     "cucumber.js ./features -r ./steps"
  },
  # To run the script through command line
npm run cucumber.js ./features -r ./steps
  
  # It will run on window and mac
  "scripts": {
    "cucumber": "cucumberjs ./features -r ./steps"
  },

# To run the script through command line
npm run cucumber # cucmber refer to the name given under script.


test
