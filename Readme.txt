Steps to be followed
To run the chat, you need to have node.js installed, so that the node and npm commands can be called from your terminal. Download the code and unzip the archive to a folder called nodejs-private-webchat. After this, navigate to the folder you’ve created from your terminal:

cd nodejs-private-webchat/
Running the ls (or dir if you are on windows) command should show app.js, package.json and the other files from the archive. Then, run this command to download all the libraries that the chat system uses:

npm install
This will install all the dependencies that are described in package.json. This may take one or two minutes. When it’s done, run the following command to start your very own local chat, which you can see on http://localhost:8080

node app.js
Hit ctrl+c to stop it. 