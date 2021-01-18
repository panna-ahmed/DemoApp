# demoapp

Technologies used: <br/>
asp dotnet core 5 <br/>
angular 9 <br/>
sql server <br/>
<br/>
Setup:
<br/>
Install nodejs from https://nodejs.org/en/download/
<br/>
Install dotnet from https://dotnet.microsoft.com/download/dotnet/5.0
<br/>
In the client\ssl folder there is a server.crt file which you will need to run and put it in trusted to make it run on https. 
<br />
1. Double click server.crt
2. Click Install Certificate
3. Select current user and click next
4. Select place all certificates in the following store and click Browse
5. Select "Trusted Root Certification and Authorities" and click ok.
6. Click Next
7. Click Finish
<br/>
<br/>
How to run:
<br/>
1. create a new database on sql server
<br/>
2. update appsettings.development.config and set DefaultConnection with the connection string. 
<br/>
3. Open terminal on the demoapp folder.
<br/>
4. run -> cd api
<br/>
5. run -> dotnet ef database update
<br/>
6. run -> dotnet run
<br/>
7. Open another terminal on the demoapp folder.
<br/>
8. run -> cd client
<br/>
9. run -> npm install 
<br/>
10. run -> ng serve 
<br/>
<br/>
Output:<br/>
<img alt="Homepage" src="../master/screenshots/0NHQg3j5V8.png?raw=true">





