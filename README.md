# Swarm

[![Build Status](https://ci.jenkins.io/buildStatus/icon?job=Plugins/swarm-plugin/master)](https://ci.jenkins.io/job/Plugins/job/swarm-plugin/job/master/)
[![Jenkins Plugin](https://img.shields.io/jenkins/plugin/v/swarm.svg)](https://plugins.jenkins.io/swarm)
[![Jenkins Plugin Installs](https://img.shields.io/jenkins/plugin/i/swarm.svg)](https://plugins.jenkins.io/swarm)
[![Dependabot Status](https://api.dependabot.com/badges/status?host=github&repo=jenkinsci/swarm-plugin)](https://dependabot.com)

This plugin enables nodes to auto-discover a nearby Jenkins master and
join it automatically, thereby forming an ad-hoc cluster. Swarm makes it
easier to auto-scale a Jenkins cluster by spinning up and tearing down
new nodes, since no manual intervention is required to make them join or
leave the cluster.

See [the Swarm Plugin page](https://wiki.jenkins.io/display/JENKINS/Swarm+Plugin)
on the Jenkins wiki for more information.

### Documentation

* [Proxy Configuration](docs/proxy.md)
* [Logging](docs/logging.md)
