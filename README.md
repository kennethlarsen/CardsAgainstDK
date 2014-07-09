##NodeJS Against Humanity

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/2.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/2.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/2.0/">Creative Commons Attribution-NonCommercial-ShareAlike 2.0 Generic License</a>.

NodeJS implementation of Cards Against Humanity. Here's a screenshot:


##Run Locally

Install all the dependencies:

    npm install (you may need to prefix this with sudo if you're on Mac)

Run the app:

    node server.js

Then navigate to `http://localhost:3000`

If you want tests to execute every time you change a file:

    jasmine-node ./spec/describe_Game_spec.js --autotest --watch ./game.js
    
To run the E2E tests you first must install protractor. see: https://github.com/angular/protractor/blob/master/docs/getting-started.md

If you want the server to load up everytime you change the back end:

    npm install -g nodemon

Then run the following instead of `node server.js`:

    nodemon server.js

