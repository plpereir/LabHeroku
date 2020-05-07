# LabHeroku
this repository has the purpose of storing the development labs carried out in node.js and deploying the free development account at heroku.

url app na heroku: https://blooming-earth-58966.herokuapp.com/

------ Deploy steps: ------

#1 Logging Into Heroku:
heroku login;

#2 Creating a Simple Node Application:
git clone https://user:password@github.com/plpereir/LabHeroku.git

#3 Folder Structure App:
- public/ (css, js e img files)
- views/ (index.ejs)
- .gitignore
- package.json
- server.js

#4 Prepare package.json

#5 Install packages and dependences: npm start

#6 Prepare server.js

#7 update index.ejs and css, js, img files

#8 Local test:
node server.js -> Our app is running on http://localhost:8080

------ Deploying Your Node App at Heroku: ------

#1 create the remote repository:
heroku create

#2 Deploying Code: 
git push heroku master

#3 Ensure One Instance Is Running (Our application is ready!):
heroku ps:scale web=1

#4 Defining a Specific Run Command:
create a Procfile in the root of your project and define the following:
web: node server.js

#5 View Our Application in Browser:
heroku open


More Details:

https://devcenter.heroku.com/articles/getting-started-with-nodejs#deploy-the-app

https://devcenter.heroku.com/articles/deploying-nodejs


------ Main Commands------

- Heroku

check hours used free account:
heroku ps -a blooming-earth-58966

run local:
heroku local web

view log:
heroku log

open browser (app at heroku):
heroku open

provider dyno to use:
heroku ps:scale web=1

create app:
heroku create

login heroku account:
heroku login


- Git

addtional files:
git add .

commit changes:
git commint -m "update index and server"

push changes:
git push https://user:password@github.com/plpereir/LabHeroku.git

push changes at heroku:
git push heroku master




