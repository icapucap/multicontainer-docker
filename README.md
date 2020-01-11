# multicontainer-docker

A Fibonacci Calculator created using Node,Postgres,Redis,Nginx. Multiple docker containers are spun up to host the same.
Also built a CI + CD pipeline from scratch with Github, Travis CI, and AWS. Learned to use ElasticBeanStalk, ElastiCache, VPC and RDS on AWS as a part of deploying the same.
Additionally I have also used volumes, hence changes made during development can be monitored on the fly by simply refreshing the browser.
# How to view

Clone the repo and cd into the folder.
```
git clone https://github.com/icapucap/multicontainer-docker.git
```
Once in the folder use docker-compose to spin up the containers 
``` 
sudo docker-compose up --build
```
Open up your browser and type in localhost:3050 and don't forget to refresh after submitting!

