--This is a django rest framework project with django as the backend and hopefully react as the frontend --

to run the project one needs to have visual studio code or whichever editor one prefers 
clone the project and open it on visual studio
on the terminal install django 
next install a virtual environment using pipenv then activate the virtual environment using pipenv shell
install djangorestframework and django-cors-headers
run the project on the terminal using the command python manage.py runserver
then navigate to the api page coz there was no webpage created to display the GET request 
you can now view the endpoints of the django rest framework created and the details as added in the database
..the project is still under development in the addition of the frontend bit

the front end bit includes ---
a frontend folder created from the command 
$ npx create-react-app frontend--this will add all the dependancies and create the frontend application 
run the command yarn start or npm start whichever works on your device
update the app.js file to by loading some mock data onto it in form of a list and use the js method map() to display all the items 

if the mock data trial is successful we head into the API and use the GET request to display the data at the endpoint of the backend django app
close the react app ( ctr c ) 
we will use axios to make HTTP requests to the API endpoint listing all todos 
$ npm install axios then import it at the top of the app.js app to use it 
the configuration for the app.js app is done in the files provided 
when you run it  gives the results of the endpoint and voila!
...success...
