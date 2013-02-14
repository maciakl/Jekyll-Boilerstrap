Jekyll Boilerstrap
==================

A simple Jekyll blog template using modern front end development standards:

* [HTML5 Boilerplate][h5]
* [Modernizr][mo] 
* [Twitter Bootstrap][tb]

Note: None of the above are included in this repository. These components are managed as third party
dependencies using [Twitter Bower][bo] front end package manager.

Dependencies
------------

This project has the following development time dependencies:

* [Ruby][ru]
* [Ruby Gems][gm]
* [Jekyll][jk]
* [Node.js][no]
* [Twitter Bower][bo]

Optional dependencies include:

* [GruntJS][gr]


Getting Started
---------------

To get started, first clone the repository:

    git clone https://github.com/maciakl/Jekyll-Boilerstrap.git

Next download the prerequisites using [Bower][bo]:

    bower install

This will create the `components` directory and install Bootstrap, Modernizr and jQuery inside.

Optionally install [Grunt][gr] dependencies if you are planning to use it:

    npm install

Now compile the blog using:

    jekyll --no-auto

This will compile your blog into the `_site` directory.

Screenshots
-----------

Front page:  
  
![Front Page][screen1]
  
Individual post:  

![Individual Post][screen2]


[h5]: http://html5boilerplate.com/
[tb]: http://twitter.github.com/bootstrap/
[mo]: http://modernizr.com/

[ru]: http://www.ruby-lang.org/en/
[gm]: https://rubygems.org/
[jk]: http://jekyllrb.com/

[no]: http://nodejs.org/
[bo]: http://twitter.github.com/bower/
[gr]: http://gruntjs.com/

[screen1]: http://i.imgur.com/3A2fimN.png "Front Page"
[screen2]: http://i.imgur.com/pPX62r5.png "Individual Post"
