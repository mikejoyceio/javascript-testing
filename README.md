#Feed Reader Testing

######Project Overview

Project #6 of Udacity's [Front-End Web Developer Nanodegree](https://www.udacity.com/course/front-end-web-developer-nanodegree--nd001).

The task was to learn about TDD (test-driven development) by piecing together an incomplete Jasmine test suite for a web-based application that reads RSS feeds.

##Getting Started

######Live

Point your browser to http://javascript-testing.mikejoyce.io/

######Locally

**1.** Clone this repo:

```
$ git clone https://github.com/mikejoyceio/javascript-testing
````

**2.** Serve the application:

```
$ python -m SimpleHTTPServer
```

Detailed Python Simple Server instructions can been found [here](https://docs.python.org/2/library/basehttpserver.html).

**3.** Open the application:

```
$ open "http://localhost:8000"
```

NOTE: If you would like to serve the application locally without Python Simple Server, make sure to serve on port 8000 otherwise the Uber API will not return ride price estimates.

##Additional Tests

An additional test suite has been added and contains specs to ensure a loading animation is visible when a feed is being loaded and hidden either when the feed loads successfully or if there is an error in the AJAX request. All of the specs in this suite will fail as this feature has yet to be implemented.

Detailed code comments on what the individual specs are testing for can be found in within the '[Loading Animation](https://github.com/mikejoyceio/javascript-testing/blob/master/jasmine/spec/feedreader.js#L261)' describe function on [line 261](https://github.com/mikejoyceio/javascript-testing/blob/master/jasmine/spec/feedreader.js#L261) of [feedreader.js](https://github.com/mikejoyceio/javascript-testing/blob/master/jasmine/spec/feedreader.js).

##Resources

- [Jasmine Documentation](http://jasmine.github.io/2.1/introduction.html)
- [jQuery](https://api.jquery.com/)
