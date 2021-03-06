title: Web Frameworks
category: page
slug: web-frameworks
sort-order: 02


# Web frameworks
A web application framework is a code library that make a developer's life
easier when building reliable, scalable and maintainable web applications.


## Why are web frameworks necessary?
Web frameworks encapsulate what developers have learned over the past twenty
years while building dynamic web applications. Frameworks make it easier
to reuse code for common HTTP operations and to structure your code so that 
it is maintainable.


## Common web framework functionality
Frameworks provide functionality in their code or through extensions to 
perform common operations required to run web applications. These common 
operations include:

1. URL routing
2. HTML, XML, JSON, and other output format templating
3. Database manipulation
4. Security against Cross-site request forgery (CSRF) and other attacks

Not all web frameworks include code for all of the above 
functionality. Frameworks fall somewhere between simply executing a 
single use case and attempting to be everything to every developer with
increased complexity. Some frameworks take the "batteries-included" approach 
where everything possible comes bundled with the framework while others 
have a minimal code library that plays well with extensions.

For example, the Django web application framework includes an 
Object-Relational Mapping (ORM) layer that abstracts relational database 
read, write, query, and delete operations. However, Django's ORM
cannot work without significant modification on non-relational databases such 
[MongoDB](http://www.mongodb.org/).
Some other web frameworks such as Flask and Pyramid are easier to
use with non-relational databases by incorporating external Python libraries.
There is a spectrum between minimal functionality with easy extensibility and
including everything in the framework with tight integration.


## Web Framework Resources
* "[What is a web framework?](http://www.jeffknupp.com/blog/2014/03/03/what-is-a-web-framework/)"
  by [Jeff Knupp](https://twitter.com/jeffknupp)
  is a in-depth explanation of what a web framework is and their relation
  to web servers.

* [Pyramid](http://www.pylonsproject.org/), 
  [Falcon](http://falconframework.org/),
  [web.py](http://webpy.org/) are the most common Python web frameworks other
  than Django, Flask and Bottle.

* This [roundup of 14 minimal Python frameworks](http://codecondo.com/14-minimal-web-frameworks-for-python/)
  contains both familiar and less known Python libraries.

* The [web micro-framework battle](http://www.slideshare.net/r1chardj0n3s/web-microframework-battle/)
  presentation goes over Bottle, Flask, and many other lesser known Python
  web frameworks.


### Which web framework do you want to learn about?
