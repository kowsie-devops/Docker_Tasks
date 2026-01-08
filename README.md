# Docker_Tasks

1. Containerize a simple flask app that says "Hello World!"
      Steps:
             Create a new folder and add app.py with basic flask app.
             Write a dockerfile for it and build image and run the container.


2. Create a Dockerfile that uses ubuntu, prints hello docker and exits immediately.


3. python calculator app: use python 3.10-slim and copy calc.py and run it using CMD.


4. Node.js web app: use node 18 alpine, install dependencies, export port 8000/3000 and start app with npm start.


5. static website using nginx: copy HTML files, serve using nginx, expose port 80.


6. java JAR application: use openjdk21, copy app.jar and run with java -jar.


7. Environment variables: set APP_ENV=production and print it while container starts.


8. non-root user: create a user appuser and run container as non-root.


9. reduce image size: convert a normal image to alpine and compare image sizes.


10. multi stage build: build a node app, serve it using nginx and only final build files in image.


11. healthcheck: add HEALTHCHECK and validate app is running.
