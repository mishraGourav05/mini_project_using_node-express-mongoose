# mini_project_using_node-express-mongoose

LifeStyle – An Express Application 
INTRODUCTION 
Lifestyle is an online single page e-commerce, a express application which is running on 
NodeJS. It has 6 sections header, home, about, product, a map, contact and footer. 
Handlebars are used to write templates for rendering HTML-pages. Handlebar is a pure 
rendering engine. Bootstrap framework is used for styling. It contains CSS- and JavaScript based design templates for forms, buttons, navigation, and other interface components. In the contact section the input is stored in a noSQL database i.e., mongoDB and the gui used 
for querying the data is mongoDB compass.

TECH STACK 
● NodeJs and Express for backend. 
● MongoDB as a database. 
● HTML, CSS, Bootstrap and Handlebars for user interface. 
● MongoDB compass GUI
● Mongoose, Object Data Modelling is used schema validation and representation of objects.

PROJECT SETUP STEPS 
● Download and setup nodejs , npm, bootstrap and mongoDB packages on your system 
o https://nodejs.org/en/
o https://www.npmjs.com/
o https://www.mongodb.com/
o https://www.bootstrap.com/
● Download the project code. 
● Once the code is downloaded, follow these steps (in terminal) 

Terminal 1 (Keep mongoDB server running) 
o $ mongod (run mongoDB server running in a separate terminal) 

Terminal 2 (Run Node Js server)
o $ cd e-commerce-webapp (move into the directory)
o $ npm install (updates packages used if there are any new updates) 
o $ npm run dev (start the server)
Web Browser (Open any web-browser)
● http://localhost:3000/ ( to see the project) 
 
 
 PROJECT STRUCTURE 
├── node modules/ (contains all node modules)
│ 
│ 
│ 
├── public/
│ ├──css/
│ │ └──style.css
│ └──images/ (contains all images)
│ 
│ 
├── src/
│ ├── app.js
│ ├──db/
│ │ └──conn.js
│ └──models/
│ └──usermsg.js
├── templates/
│ ├──partials/
│ │ ├──about.hbs
│ │ ├──contact.hbs
│ │ ├──map.hbs
│ │ ├──navbar.hbs
│ │ └──service.hbs
│ │
│ ├──views/
│ └──index.hbs
│
├── package-lock.json
└── package.json
