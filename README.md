# Overview

This is building off from an already existing website for the ward I currently attend while going to Brigham Young University - Idaho.

The purpose of these additions is to dynamically input and recieve weekly changing values such as who is speaking to the congregation, hymns sung, who gives the prayers, etc.

This will not only make my job easier as it is part of my responsibility to be updating these weekly, but will also make it easier for those in the future who have the same responsibilities as I do now.

[Software Demo Video](https://youtu.be/-ZlVcq7NlT8)

# Web Pages

I made a form where it recieves input from the user, then pushes all of the provided information to the database using the custom made API.

I also made a page where it makes a request using the API when the page loads to dynamically update the information on that page.

# Development Environment

* Windows 10 machine - 64 bit
* VS Code
* WordPress
* Divi Theme
* MongoDB
* Heroku
* Vanilla JavaScript

# Useful Websites

* [Heroku Docs](https://devcenter.heroku.com/categories/reference)
* [MongoDB Docs](https://www.mongodb.com/docs/)

# Future Work

* Have the placeholder for the form page be the last entry in the database, and if the user does not enter anything for that field, then re-post the same value.
