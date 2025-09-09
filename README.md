A social media website with focus on registration, login, security, user posts

	Techs:
	
		JavaScript, Node.js, Express.js, MongoDB, Mongoose, 
		Json Web Token (JWT), route, pagination, 
		async / await, REST API, Docker



How to run

	1. build `socialapp` Docker image (if the image has not been created yet)
	
		docker build . -t socialapp
	
	2. start Docker containers (socialapp and mongo)
	
		docker-compose up
	
	3. launch http://localhost:3000 in a browser
	
		- register / login
		
		- create posts



Reference:

[Node.js & MongoDB: Developing Back-end Database Applications](https://www.coursera.org/learn/intermediate-back-end-development-with-node-js-mongodb?specialization=ibm-full-stack-javascript-developer) (a course of [IBM Full-Stack JavaScript Developer Professional Certificate](https://www.coursera.org/professional-certificates/ibm-full-stack-javascript-developer))
