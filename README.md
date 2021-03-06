# ProtoCount Accounting App (front end)

[Live on Heroku](http://protocount.herokuapp.com) 

Please use the following login details to access the app and experiment:

> Username: protocount  
> Password: password

### Description
Accounting Single Page Application(SPA) built using the following front-end frameworks:
1) react (particularly react hooks)
2) react-router
3) bootstrap. 

I used [Create-React-App](https://github.com/facebook/create-react-app) as the development and build tool. I built the app to mimic functionalities of off-the-shelf accounting softwares used by SMEs (Small Medium Enterprises). The back-end is built using Node.js and Mysql database. See [protocount-nodejs-mysql](https://github.com/mseong123/protocount-nodejs-mysql) for repository.

### Quick Installation/Usage

1) Clone this repository to target local folder and npm install dependencies. This will install create-react-app tool locally for development and build purpose.

```
git clone https://github.com/mseong123/protocount-create-react-app.git <target folder>
cd <target folder>
npm install
```
2) To initiate development environment type `npm start` in repository local folder and the live app will be pushed to browser. Upon any amendments to source files, app will reload automatically in browser.  

*For development purpose, you need to install the back end (web server and database) in order for the app to work. Follow set up instructions on [protocount-nodejs-mysql](https://github.com/mseong123/protocount-nodejs-mysql).* 

3) source files and other assets are all included in /src folder. **Only amend these files and nothing else**

4) type `npm run build` to compile source codes into HTML,CSS and JS codes for deployment. These files are contained in /build folder. For production purpose, copy and paste these built files into /public folder in local repository of the back end [protocount-nodejs-mysql](https://github.com/mseong123/protocount-nodejs-mysql) and follow instructions there to launch app. 


**See [Create-React-App](https://github.com/facebook/create-react-app) for detailed guidelines on usage of create-react-app tool**

\
\
Any problems or bugs, please message me. Thanks!


