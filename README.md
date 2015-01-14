magnolia-templating
===================

[Magnolia](http://www.magnolia-cms.com) templating kit based on [Foundation for Sites](http://foundation.zurb.com/)

Are we A-OK?
[![Build Status](https://travis-ci.org/gtenham/magnolia-templating.svg?branch=master)](https://travis-ci.org/gtenham/magnolia-templating)

##

## Prerequisites
* [git](http://git-scm.com/)
* [java 7](http://java.com)
* [Maven 3](http://maven.apache.org)

## Quickstart
```shell
git clone https://github.com/gtenham/magnolia-templating.git magnolia-templating
cd magnolia-templating
mvn clean install
```
This results in a war-file which can be deployed to any servlet container like Tomcat.
Rename war-file to "magnoliaAuthor" to have a Magnolia author instance using embedded Derby database.

For more information on running Magnolia look here[http://documentation.magnolia-cms.com/display/DOCS/Creating+a+custom+bundle][1]

[1]: http://documentation.magnolia-cms.com/display/DOCS/Creating+a+custom+bundle#Creatingacustombundle-Runtheproject

