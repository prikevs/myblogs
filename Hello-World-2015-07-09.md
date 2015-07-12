---
title: Hello World
summary: 
  This is my first article of this blog. I will show you how to use
  Flask and Bootstrap to build a blog site, just like this one :)
tags:
  - python
  - flask
  - bootstrap
...

#Hello World#

##Introduction##
*   Soon before, A thought come into my mind that I want to write a blog 
    site on my own, including both the back-end and the front-end 
    [KevBlog](https://github.com/prikevs/KevBlog/). 
    Because of my favor of Python, I chose to use frameworks written in 
    Python like Django, Tornado web.py and Flask etc. I chose Flask for the 
    following reasons:
> 1.  It is micro, not like Django.
> 2.  It has many extensions, and many of them are plugable.
> 3.  It is quite simple, and can be learned quickly.
    

*  And the front-end, I chose Bootstrap.
> Bootstrap makes front-end web development faster and easier.
> It is made for folks of all skill levels, devices of all shapes,
> and projects of all sizes.

##Steps##
1.  Analyze the requirements. Find out which functions do I need.
>   *  Show title, summary, publish time for all articles on the index
>   *  Every article has a collection of *(title, summary, content, publish 
       time, tags)*
>   *  The relationship between articles and tags is 'Many-to-Many', which
       means every article may belong to more than one tags, and of course,
       each tag will contain more than one articles.
>   *  Use markdown to write articles.
>   *  Show some other infomation just like 'About me', copyright etc.

2.  Write the back-end code.
>   *  Logical relation between different data in *models.py*
>   *  Handle URL requests in *views.py*

3.  Write the front-end code. And I am quit not good at front-end 
    programming :-( I just spent half a day learning my front-end courses 
    on [imooc.com](http://www.imooc.com)

##To be done##
> *  Comment system.
> *  Administrator platform.
> *  Improvement of front-end design.

##Conclusion##
> *  This is my blog, not just owned by me, but also written by me. I will
     continue updating articles as I learn new knowledge.
> *  And of course, this is just the beginning!
