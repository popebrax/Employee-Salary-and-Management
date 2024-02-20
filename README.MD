This is an Employee Salary and Management app i created for my Final Year Project, Computer Science following a tutorial from https://youtu.be/bbizRxjyz64?si=rJUHFoHTooocbBLn, where i made a few modifications of my own.


To run the following app, 
1. Clone the repository and cd into the project folder.
2. Do 'npx expo install' at the root folder
3. Navigate to the api folder and do 'npm install'
4. Once all dependencies are installed you need to start 2 terminals, one from the root folder and another from the api folder.
5. In the root folder do 'npx expo start' and with that you can run an android emulator or if you prefer you can use the expo go app on your phone.
PLEASE NOTE: When using the expo go app, you need to connect your pc via a hotspot to your phone, then run ifconfig on terminal and replace 'localhost' with the the ip address in the following '.js' files:
        1. /api/index.js
        2. /app/(home)/(Replace [local host](http://localhost) with the ip address in all the files within this directory)
        
6. Then you need to create a mongodb account if you lack one, choose the free version, create a cluster then a database, in the connect section choose 'connect vscode' and paste the link in the /api/index.js under [mongoose
  .connect("mongodb+srv://<your-cluster-name>:<your-password>.dgyyr9a.mongodb.net/"]     
7. Then create a new terminal and cd into api folder then do 'npm start'
8. With this everything should run ok.  
9. My portfolio is https://njdaka.github.io/, if you want to link up for a project, reach out
