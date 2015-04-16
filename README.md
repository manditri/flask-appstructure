# Flask Application Structure

### Structuring large web application(or collection of applications) using the python flask framework ###

As an effort to breakup large monolithic codebase of flask application, I have tried to come up with a structure that helps building discrete components(domains) as individual applications which can be dispatched together using various techniques.

**Some advantages to this approach-**
* DRY- create apis that can be shared with variety of clients
* Easier to introduce changes, refactor in a loosely coupled set of applications
* Scale out individual applications with ease
* Better design for TDD

**Some inspiration that lead me to this-**
* A monolithic codebase at workplace with extreme tight coupling of components
* [How I structure my flask applications] (http://mattupstate.com/python/2013/06/26/how-i-structure-my-flask-applications.html)
* [Flask Patterns](https://www.youtube.com/watch?v=KOvgfbBFZxk)
* [Flasky-Goodness](https://speakerdeck.com/kennethreitz/flasky-goodness)
