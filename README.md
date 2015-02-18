Modern Web Template
===========

**AngularJS - Scala - Play - Guice - PlayReactiveMongo**

A full application stack for a Modern Web application, lets review the components:

* **AngularJS** - client side javascript framework for creating complex MVC applications in Javascript,
fronted with Twitter bootstrap CSS framework, because well, im not a web designer.
  * Take a look at what the google cool kids are upto here : [AngularJS](http://angularjs.org/)

* **Bootstrap** - Bootstrap components written in pure AngularJS
  *  [http://angular-ui.github.io/bootstrap/](http://angular-ui.github.io/bootstrap/)

* **CoffeeScript** - CoffeeScript is an attempt to expose the good parts of JavaScript in a simple way.
  *  [http://coffeescript.org/](http://coffeescript.org/)

* **PlayFramework** - currently using 2.3.4 with the scala API
  *  [PlayFramework Docs](http://www.playframework.com/documentation/2.3.x/Home)

* **Guice** integration for Dependency injection,
  * Special thanks to the typesafehub team for their activator : [Play-Guice](http://www.typesafe.com/activator/template/play-guice)

* **PlayReactiveMongo** gives interaction with MongoDB providing a non-blocking driver as well as some useful additions for handling JSON.
  * Check out their GitHub: [Play-ReactiveMongo](https://github.com/ReactiveMongo/Play-ReactiveMongo)



Getting Started
----------

To run the application, there are some pre requisites.

1)You should have a local instance of mongodb running, which is listening on port 20717. That is the default.
2)You should install play
3)run the following command in the folder
"./activator run"
4) This should launch the application listening on port 9000.