# docker-demo
Minimal Docker application sample based on https://nodejs.org/en/docs/guides/nodejs-docker-webapp/


Note: Replace 'pikala' with your own Docker Hub user id! 

**Run locally**

npm install
node server.js 


**Build Docker Image**

docker build . -t pikala/docker-demo
	

**Run with Docker**

docker run -p 8888:8080 -d pikala/docker-demo:latest

docker ps 

docker stop [container]
		

**Push to Docker Hub** 

docker login (if needed)

docker push pikala/docker-demo:latest


