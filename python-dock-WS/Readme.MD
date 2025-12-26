1) we are creating the web server by using the python code
2) code is stored in app.py
3) Dockerfile available in the repo for building the docker image
4) by using that docker image, we will run the webserver
5) rest of the commands are below given 
docker build -t pythondocker 
docker rm -f flask_container 2>/dev/null
docker run -d --name flask_container -p 5000:5000 pythondocker
6) we need to push the current docker file to the docker repo
