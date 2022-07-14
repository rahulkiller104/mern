<h1 align="center">
🌐 Gallery Website
</h1>
<p align="center">
MongoDB, Expressjs, React, Nodejs
</p>


> MERN is a fullstack implementation in MongoDB, Expressjs, React, Nodejs.

MERN stack is the idea of using Javascript/Node for fullstack web development.

## clone or download
```terminal
$ git clone https://github.com/amazingandyyy/mern.git
$ npm i
```

## project structure
```terminal
LICENSE
package.json
server/
   package.json
   .env (to create .env)
client/
   package.json
...
```

# Usage (run fullstack app on your machine)

## Prerequisites
- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^10.0.0
- [npm](https://nodejs.org/en/download/package-manager/)

notice, you need client and server runs concurrently in different terminal session, in order to make them talk to each other

## Client-side usage(PORT: 3000)
```terminal
$ cd client   // go to client folder
$ npm i       // npm install packages
$ npm run start // run it locally 



## Server-side usage(PORT: 8000)
```terminal
$ cd server   // go to server folder
$ npm i       // npm install packages
$ npm start // run it locally
```

## Deploy Server to [Heroku](https://dashboard.heroku.com/)
```terminal
$ npm i -g heroku
$ heroku login
...
$ heroku create
$ npm run heroku:add <your-super-amazing-heroku-app>
// remember to run this command in the root level, not the server level, so if you follow the documentation along, you may need to do `cd ..`
$ pwd
/Users/<your-name>/mern
$ npm run deploy:heroku
```

### frontend deployed on firebase
   (https://hackearth-assignment-frontend.web.app/)


# Dependencies(tech-stacks)
Client-side | Server-side
--- | ---
axios: ^0.15.3|body-parser: ^1.15.2
react: ^16.2.0 | dotenv: ^2.0.0
react-dom: ^16.2.0 | express: ^4.14.0
react-router-dom: ^4.2.2 | mongoose: ^4.7.4


Email Me: rahulkumar10433@gmail.com (welcome, say hi)

### License
[MIT](https://github.com/amazingandyyy/mern/blob/master/LICENSE)
