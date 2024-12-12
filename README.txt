This is the YouTube video I followed to set up the server: https://www.youtube.com/watch?v=ILviQic0c8g
(Only clip you will need: Starts @4:10, Ends @9:20)

Sorry for the inconvenience but it should only take 5 minutes to set up :(

Here are my instructions...

To Download node.js:
1. For Mac: if not already installed install homebrew
	https://brew.sh/

   For Windows: if not already installed install chocolatey
	https://chocolatey.org/install

To Download node.js:
1. Download node.js
https://nodejs.org/en/download/package-manager


To Set Up node.js:
1. Open up the project


2. Start a New Terminal


3. Change the directory to User
	ie: cd User (might have to cd Project first)


4. Type: npm init [enter]


5. Press enter after each option until there aren't any more (this just makes all the settings set to standard)


6. Type: npm i express els


7. Type: npm I --save-dev nodemon dotenv npm


8. Create .env file

9. In the .env file
    Type:
    SESSION_SECRET=secret

10. Make sure that this is in the .gitignore file:
    .env
    node_modules

11. In package.json, in "scripts", replace the code in the { } with "devStart": "nodemon server.js"


To Run the Website:
1. Open a browser and enter localhost:3000 in the address bar


2. Run a New Terminal in vs code


3. Navigate to Users if needed
	ie: cd Users


4. Type: npm run devStart






