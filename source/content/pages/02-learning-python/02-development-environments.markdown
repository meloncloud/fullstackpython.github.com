title: Development Environments
category: page
slug: development-environments
sort-order: 1102
choice1url: /introduction.html
choice1icon: fa-fast-backward fa-inverse
choice1text: Let me start over from the Full Stack Python introduction.
choice2url: /best-python-resources.html
choice2icon: fa-book fa-inverse
choice2text: Show me a list of the best Python learning resources.
choice3url: /web-frameworks.html
choice3icon: fa-code fa-inverse
choice3text: I want to get started coding a Python web app.
choice4url:
choice4icon:
choice4text:


# Development Environments
A development environment is a combination of a text editor and the Python
interpreter. The text editor allows you to write the code. The interpreter
provides a way to execute the code you've written. A text editor can be
as simple as Notepad on Windows or more complicated as a complete integrated
development environment (IDE) such as 
[PyCharm](https://www.jetbrains.com/pycharm/) which runs on any major 
operating system.


## Why is a development environment necessary?
Python code needs to be written, executed and tested to build
applications. The text editor provides a way to write the code. The 
interpreter allows it to be executed. Testing to see if the code does what
you want can either be done manually or by unit and functional tests. 


## A development environment example
Here's what I (the author of Full Stack Python, 
[Matt Makai](/about-author.html)) use to develop most of my Python 
applications. I have a Macbook Pro with Mac OS X as its base operating 
system. [Ubuntu 14.04 LTS](/operating-systems.html) is virtualized on top 
with [Parallels](https://www.parallels.com/). My code is written in 
[vim](http://www.vim.org/) and executed with the 
[Python 2.7.x](https://www.python.org/download/releases/2.7.8/) interpreter
via the command line. I use virtualenv to create separate Python interpreters
with their own isolated
[application dependencies](/application-dependencies.html) and
[virtualenvwrapper](http://virtualenvwrapper.readthedocs.org/en/latest/)
to quickly switch between the interpreters created by virtualenv.

That's a common set up but you can certainly write great code with a much
less expensive set up or a cloud-based development environment.


## Open source development environments
* [vim](http://www.vim.org/) is my editor of choice and installed by default
  on most \*nix systems.

* [emacs](http://www.gnu.org/software/emacs/) is another editor often used
  on \*nix.

* [PyDev](http://pydev.org/) is a Python IDE plug in for 
  [Eclipse](https://www.eclipse.org/).

* [Sublime Text](http://www.sublimetext.com/) versions 2 and 3 (currently
  in beta) are popular text editors that can be extended with code completion,
  linting, syntax highlighting and other features using plugins.

* [Atom](https://atom.io/) is an open source editor built by the 
  [GitHub](https://github.com) team.


## Python-specific IDEs
* [PyCharm](https://www.jetbrains.com/pycharm/) is a Python-specific IDE
  built on [JetBrains](https://www.jetbrains.com/)' platform. There are
  free editions for students and open source projects.

* [Wing IDE](https://wingware.com/) is a paid development environment with
  integrated debugging and code completion.

* [Komodo](http://komodoide.com/)


## Hosted development environment services
In the past couple of years several cloud-based development environments
have popped up. These can work great for when you're learning or stuck on
a machine with only a browser but no way to install your own software. Most
of these have free tiers for getting started and paid tiers as you scale
up your application.

* [Nitrous.io](https://www.nitrous.io/)

* [Cloud9](https://c9.io/)

* [Terminal](https://www.terminal.com/)

* [Koding](https://koding.com/)


## Development environment resources
* If you're considering the cloud-based development environment route, check
  out this 
  [great article comparing Cloud9, Koding and Nitrous.io](http://readwrite.com/2014/08/14/cloud9-koding-nitrousio-integrated-development-environment-ide-coding)
  by Lauren Orsini. She also explains more about what a cloud IDE is and is
  not.

* Real Python has an awesome, detailed post on 
  [setting up your Sublime Text 3 environment](https://realpython.com/blog/python/setting-up-sublime-text-3-for-full-stack-python-development/)
  as a full-fledged IDE.

* The [Hitchhiker's Guide to Python](http://docs.python-guide.org/en/latest/dev/env/)
  has a page dedicated to development environments.

* [Choosing the best Python IDE](http://pedrokroger.net/choosing-best-python-ide/)
  is a review of six IDEs. PyCharm, Wing IDE and PyDev stand out above the
  other three in this review.

* [PyCharm: The Good Parts](http://nafiulis.me/pycharm-the-good-parts-i.html)
  shows you how to be more efficient and productive with that IDE if it's
  your choice for writing Python code.


