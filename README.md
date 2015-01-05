Postman for Node.js
=======
- Homepage (Google Chrome app) - http://www.getpostman.com
- Blog (Tutorials/Updates) - http://blog.getpostman.com
- Documentation - http://www.getpostman.com/docs/

About Postman for Node.js
=======
Postman for Node.js is a fork of the popular Postman app for Google Chrome. Its goal is to help you be more efficient while working with HTTP APIs.

While the original Postman ran only in your local browser, Postman for Node.js runs on a Node.js server, which means it can be deployed anywhere for the purpose of providing a SaaS solution for testing APIs. For example, Postman can now be used to test APIs that otherwise might be inaccessible due to firewall restrictions.

Features
========

Create requests quickly.

- Compact layout
- HTTP requests with file upload support
- Formatted API responses for JSON and XML
- HATEOAS support
- Image previews
- Request history
- Basic Auth and OAuth 1.0 helpers
- Autocomplete for URL and header values
- Key/value editors for adding parameters or header values. Works for URL parameters too.
- Use environment variables to easily shift between settings. Great for testing production, staging or local setups.
- Keyboard shortcuts to maximize your productivity

Document and share APIs.

- Use collections to organize requests.
- Document requests inside collections. You can even store entire HTML notes. Postman uses Bootstrap so you can use it too to style your notes.
- Download and share collections with your team of developers.

Installing
=========================

Postman for Node should run easily in any Node.js capable environment.

Running locally
-------------------------
1. `git clone` this repository
2. `npm install` to grab all of the dependencies
3. `npm start` to run the app
4. Launch a browser and visit `http://localhost:3000`
 
Postman for Node should also run more or less unmodified on Platform-as-a-Service (PaaS) providers that support Node.js natively.

Building and Developing
=========================
1. Install the dependencies
	```
	sudo npm install -g grunt grunt-cli
	```

2. Generate the template.js and request.js files by running grunt. You can watch the folder for changes using:
	```
	grunt watch
	```
3. For misc. grunt tasks, take a look at `grunt.js`.

Submitting bugs
===============
Simply open a new issue at: https://github.com/mhamann/postman-node/issues
