---
layout: post
title: 🐴 Django Adding Pages to a Site 🐴 
tags: python
---

## 📅 Today's topics

- Adding a user detail page to our site.
    4 parts to look at when adding a new page:
    - `models.py` - you may or may not need to change the models.
    - `urls.py` - you will need to add a url for each page you add. Note: when we add JS later, some of these multiple pages will be combined into one page.
    - `views.py` - your new url will call a view, and you need to write that view, which will render a template and pass any data needed from the database in the context.
    - `templates/`- you will want to add a template (html file) that extends the base template and is the template called by your new view.

    _The order in which you do these things doesn't matter. This is the order that makes the most logical sense to me, but, ultimately, all these changes need to happen in order for your new page to work._


### 🎯  Project

- [Django Development Project](https://classroom.github.com/a/UnZJjRjv)
    - we will work on this all week

### 🔖 Resources

* [Pretty Printed Django Videos](https://www.youtube.com/playlist?list=PLXmMXHVSvS-DQfOsQdXkzEZyD0Vei7PKf)
- 1-10 are the ones that will be most relevant when we get back
* [Queries in Django](https://docs.djangoproject.com/en/3.2/topics/db/queries/)
* [Django ORM Cookbook](https://django-orm-cookbook-ko.readthedocs.io/_/downloads/en/latest/pdf/)


### ⭐️ EXTRA/TMI
* [Less Obvious Things to Do With the Django ORM](https://markusholtermann.eu/2019/03/less-obvious-things-to-do-with-djangos-orm/)


### 📹 Code, Slides, and Video from Class

* [Code](https://github.com/momentum-pt-team-1/examples/tree/main/todos)
* [Class Video](https://us02web.zoom.us/rec/share/wTxSQ5d13aUbEbh2nepTzXM8NqpwWIV60wOYVjTJHS57au6J5muqmSJ_AuHc_j8n.1dCzn3OoQfJ0EpZ7)

Access Passcode: QSHKRe=2

