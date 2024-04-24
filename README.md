## Before you start

This repo is a fork of [elkninja / elastic-stack-docker-part-one](https://github.com/elkninja/elastic-stack-docker-part-one).

If you need to run Elasticsearch and Kibana (and possibly other stuff too) on your machine using Docker compose, yet you're not quite sure how to do that... You should go to the original blog post: [Getting started with the Elastic Stack and Docker-Compose](https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose) and understand what it's all about ;-) 
However, if you're DAT busy, the whole idea is quite simple:

1. You clone this project to your computer
2. You open your terminal and get into the directory (folder) when it was checked out
3. (Optional) You can check out the tag that corresponds to Elasticserach version you'd like to try out (only 8.13+ supported)
4. (Optional, but highly recommended) You change in the `docker-compose.yml` whatever you need to tune (after reading the blog post)
5. Inside the directory you run `docker compose up`
6. You open your browser to go to [http://localhost:5601](http://localhost:5601).

### TL;DR:

`git clone http://github.com/pioorg/elastic-stack-docker-part-one.git && cd elastic-stack-docker-part-one && docker compose up` and then [http://localhost:5601](http://localhost:5601)

### Tuning

Really, please read the original post if you need to tune ports, certificates, type of license, memory limits, and such.

## I'd say using this for production environment is _really_ not recommended.

This repo should be cloned only to your (developer) machine for some trials, quick demos etc. 

Original README below.

----
# Getting started with the Elastic Stack and Docker-Compose

This repo is in reference to the blog [Getting started with the Elastic Stack and Docker-Compose](https://www.elastic.co/blog/getting-started-with-the-elastic-stack-and-docker-compose)

Please feel free to ask any questions via issues [here](https://github.com/elkninja/elastic-stack-docker-part-one/issues), our [Community Slack](https://ela.st/slack), or over in our [Discuss Forums](https://discuss.elastic.co/).

Pull Requests welcome :)
