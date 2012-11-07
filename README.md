mz website
==========

Usage
=====

* `mkdir contents/projects/new-project`
* if the project have images, place them inside an `images` folder on the project folder
* create an `index.md` file with the content
* thats it!

index.md file
-------------
it is possible to use metadata tags to include some aditional information on the page:

* `template: project.jade` **required**
* `title:` **required**
* `subtitle:`
* `year:` **required** 
* `video:` *vimeo id*
* `code:` *link to repo*
* `images:` *link to flickr set*
* `wiki:` *link to wiki page*



Uses
====
* [wintersmith](https://github.com/jnordberg/wintersmith)
* [less](http://lesscss.org) via [wintersmith-less](https://github.com/jnordberg/wintersmith-less)
* [underscore](http://documentcloud.github.com/underscore/)
