# angularjs-starting-kit
AngularJS starting kit with gulp, to get you up and running with as less configuration as required

Wanna use it:

- Download it as a starting point for your project
- Run "npm install" in the command prompt/terminal to get all the dependencies installed
- ***IMPORTANT!*** Change rules.json name to ".eslintrc". Otherwise the eslint will not run and the gulp task will fail
- Run "gulp" in the command prompt/terminal to get run your app!

What it does:
- Sets up a local dev server on port 1337.
- Opens up a browser window
- Concats your JS and css files, minifies, uglifies, readyfies (the last one doesn't exists) 
  and get's stuff ready for prod under dist folder
- Add a watcher that watches for any changes and refreshes the browser window.
- Adds an eslint plugin to track code errors and best practices for angularJS and notify you.
Great stuff.

What do you need to config?
Almost nothing! all you need to do manually is to add css files as you add them to your app.
The gulpfile (core file for the tasks I mentioned before) states exactly where these links should stay.
