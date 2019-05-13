---
layout: default
title:  "Django 101 - The basics"
date:   2019-05-13
categories: web-applications django
tags: [programming, software applications]
---
# Django 101 - The basics:

![django](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSz8SSwJ8YtYnNJbX_Zhb6uuzaOtZBAiVi3qkd4v6JcBgRUGUST)

I recently started working with the Django Web Framework due to the fact that I have been trying to transfer to one
of the engineering teams internally at Indeed. The framework they are using to using to build projects is Django.

Although, I am familiar with a number of MVC'ish type of web frameworks and also familiar with Python I had actually
never used Django ever before.

What I would like to accomplish in this blog is show to set up the very basics of Django Project and launch the
a local server that allows you to see the Django welcome page. The tutorial is nice but I would like to make a tutorial
that is cleaner and easier to understand/follow step by step. So lets begin:

This tutorial will be ran through on a Linux rig (Ubuntu 18.04 to be exact). I am not going to run through Mac OS/Win
installations of any requirements/dependencies here. Generally most of the Mac commands/setup should be similar/identical.

## What Version of Python is Installed?
{% highlight bash %}
moon@moona:~$ python3 --version
#-> python3.6.7
{% endhighlight %}

So now that we know we have python 3.6.7 installed lets move on to installing python virtualenv...

## Why Python Virtual Environments?

When working on creating projects we tend to run into software/library versioning issues. In to order to isolate
this project and ensure that we dont cloud the global libraries on our laptop as well as have
an isolate environment from which to run fresh from we create a virtual environment for python.

This clean virtual environment once installed will contains the barebones of python and will allow us to start including
pip libraries that match the requirements of your specific/someone else's project.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
