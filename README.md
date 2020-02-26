# onlinejudge

# COJ - (Collaborative Online Judge)
Collaborative online judge system is a forum-like web application that allows multiple users to add coding problems and collaborate on one coding problems simultaneously just like a Google Doc. Unlike Google Doc, collaborative online judge system comes with an executor server which will execute the code submitted by users.

Three major components:

- oj-client : Angular2-based front end with bootstrap
- oj-server : node.js backend platform with express middleware
- executor-server: Flask server with Docker Engine API

The project is accompanied with complete dockerization for the benefit of deployment. Make sure to set up docker before running this app on your machine.

COJ also provides RESTful APIs for obtaining, fetching and searching coding problems as well as executing user-submitted code. 

Tech Stack = {Angular, Node.js, Express, MongoDB, Redis, Javascript, Python, Nginx, Socket.io, Docker}
