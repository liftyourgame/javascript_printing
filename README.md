# Print Test Project to demonstrate a possible bug in Safari

When printing a web page in Safari from Javascript and cancelling the Print dialog then subsequent attempts to print the page again presents a native dialog:

"This webpage is trying to print. Do you want to print this webpage?"

This is not an issue with the latest version of Chrome

Is this a bug in Safari?

All of the relevant code for setting up and cleaning up printing is in: index.html in a script tag

To run the project:

npm install
npm start
