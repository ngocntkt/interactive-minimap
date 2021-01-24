# Interactive Minimap

This is a 2D web-based implementation of "search and rescue mission" game.
Try the live 2D game <a href="https://gridworld-nodejs.herokuapp.com/" target="_blank">here</a>.
+ Navigate the grid: `Arrow Keys` or `Arrow Keys + X` to speed up the move
+ Open a door: `Enter`
+ Rescue green victims: `Enter` x 5 times
+ Rescue yellow victims: `Enter` x 10 times


![Falcon Map](https://ngocntkt.github.io/visualization-map/map.png)

## Architecture

+ Front end: HTML, CSS and Javascript.
+ Back end: Node.js and MySQL.

## Database

Create a database in MySQL.

+ SQL database script can be found in: `schema/script.sql`

## Configuration

+ Install [Nodejs](https://nodejs.org/en/download/)
+ Open file `server.js` to adjust the username and password to the ones that has been configured during the mysql database installation

+ To start the server, at the root directory run:

```
$ npm start
``` 

or start server using node:

```
$ node server.js
``` 

+ Then visit: http://localhost:3000/

+ To stop the server hit: `Ctrl+C`

## Dependencies

All the used packages are listed in the file `package.json`.

To install the dependencies, at the root directory run:
```
$ npm install
```
## Contact Info
This application has been developed by Ngoc Nguyen (ngocnt@cmu.edu).
For full source code access, please contact me via email.