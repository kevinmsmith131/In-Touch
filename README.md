# InTouch
A social media platform that allows users to post pictures with captions, like posts, and follow other users whose content they wish to view.

## Premise
InTouch was built with the intent of providing a social media app that allows users to stay in touch with the people of their choosing, without anyone else being able to find their profile. The way that InTouch enforces this is by providing no way, such as searching, to find other users unless they personally provide the link to their profile. As long as a user chooses a unique username that no one is likely to guess, similar to the way one chooses a password, then only the people that they share their profile link with will be able to stay in touch with them.

## Features
### Registration Page
The registration page provides a form that allows for a user to enter an email, username, password, confirm the password, and submit this information to create their account. The app ensures that the email follows the email format of *a@b.c*, the username is not already in use, and the passwords are *at least* 5 characters and match each other. If all of these conditions are met, a new profile will be registered with the provided information. There is also a button that allows a user to navigate to the login page.

### Login Page
The login page provides a form that allows for a user to enter their email and password, and then submit this information to be logged in. The app checks for a user with this information, and if one exists, logs them in. There is also a button that allows a user to navigate to the registration page.

### Home Page 
##### Header
The header is the blue bar across the top of the page. On the left of the header there is an icon that signs the user out when clicked, in the center there is an InTouch logo that brings the user to the top of the home page when clicked, and on the right is the user's profile picture that brings the user to their profile page when clicked.

##### Following Bar
The following bar displays all of the users that the logged in user is following. Each of the displayed users can be clicked to be brought to their profile page. The header that reads "Following" at the top of the following bar can be clicked to be brought to the top of the following bar, if the user has scrolled down.
##### Feed

### Profile Page
##### Header
##### Following Bar
##### Feed

## Technologies
InTouch is a full stack web application that runs on the MERN stack. This means any data that the application stores is stored in a MongoDB database, the backend server is implemented using the Express framework, the runtime environment that the server runs on is Node.js, and the frontend is built using the React framework. The backend server adheres to RESTful API principles, and the frontend utilizes the React Context API to keep track of the currently logged in user. The application is deployed to the cloud using Heroku.

## How do I get InTouch?
You can access the application using this url: https://in-touch-heroku.herokuapp.com/

If you would like to see what the app looks like for a user who is following and is followed by many other users, you can use the login sofie@gmail.com and password 123456. 

If you would like to test out the features that make changes to a profile such as changing the username, email, password, or deleting an account, please register your own account to do so.

Creating your own profile also allows you to see how the app handles the empty defaults that are mentioned in the features section.
