# Contributing
1. Install [Node.js](http://nodejs.org/)
2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)
3. Run `./preview.sh`

Your browser should pop open and display the slides.

[Learn more about reveal.js](https://github.com/hakimel/reveal.js/blob/master/README.md)

# Proposal

## Title
Think outside the container

## Abstract
There is much more to Docker than just deploying your flagship application. Let's look at three use cases for Docker, going beyond the typical software development pipeline:

The Rackspace Cloud DNS production operations team is running Hubot, a ChatOps bot, on a Docker Swarm cluster on Carina to automate routine tasks and ping the on-call person when something is on fire at 3 AM.

Rackspace's developer documentation is open to external contributors and has streamlined the editing process with a staging environment that previews full site builds for pull requests. All of its infrastructure is hosted within Docker containers, managed by Ansible, on a CoreOS cluster.

HowToWhale is teaching Docker with zero-setup from the comfort of your web browser. Every user has an interactive sandbox, courtesy of a JupyterHub server running on their own personal Docker Swarm cluster.

Come away with ideas for how you can use Docker on the side, even if you haven't tackled Dockerizing your application.

## Agenda
* Intro: 5 minutes
* ChatOps with Nick: 10 minutes. How the CloudDNS team is using ChatOps on Carina
* Deconst with Ash: 10 minutes. How the Developer Experience team builds, tests and deploys our websites using Carina
* HowToWhale with Carolyn: 10 minutes. Learning Docker on with JupyterHub and Carina
* Q/A: 5 minutes
