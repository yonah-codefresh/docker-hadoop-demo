# docker-hadoop-demo

To get started running this project in docker using docker-compose:

* On OSX, install [virtualbox](http://virtualbox.org) and [boot2docker](http://boot2docker.io)
* Install docker-compose: ``curl -L https://github.com/docker/compose/releases/download/1.1.0/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose; chmod +x /usr/local/bin/docker-compose``.
* Start boot2docker: `boot2docker start`.
* Initialize docker environment with `$(boot2docker shellinit)`
* From the project directory, start docker-compose: `docker-compose up`. This will take some time to set up your containers the first time you run it.