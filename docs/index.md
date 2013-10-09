---
layout: docs
title: Get started
subtitle:
navgroup: docs
---
## Download Kickoff

There are a few easy ways to quickly get started with Kickoff, each one appealing to a different skill level and use case. Read through to see what suits your particular needs.

### Download from:

* Github: [.zip](https://github.com/tmwagency/kickoff/archive/master.zip)
* Git clone: `git clone https://github.com/tmwagency/kickoff.git your-project-folder`
* SVN checkout: `svn checkout https://github.com/tmwagency/kickoff your-project-folder`

## Using Grunt?
[Ruby](https://www.ruby-lang.org/en/) v2 is needed. Update using [rvm](http://rvm.io/) or [brew](http://brew.sh) (if you use a Mac), Windows users can install Ruby via [the Windows installer](http://rubyinstaller.org/downloads/), and Linux users can install it via their package manager, then install the packages below:

* Install Sass globally - `gem install sass --pre`
* Install Node from [nodejs.org](http://nodejs.org/)
* Install Grunt CLI - `npm install -g grunt-cli`
* Navigate to (`cd`) your project directory and run `npm install` which will install all Grunt's dependencies
* Run `grunt watch` to watch for changes and compile Sass/Javascript

When using Grunt with Kickoff, source maps are created for both the Javascript and Sass. Javascript is compiled to the `/js/dist` and Sass is compiled to the `/css` folder.

### Using Git?
Kickoff's [.gitignore](https://github.com/tmwagency/kickoff/blob/master/.gitignore#L28) file ignores the `/dist` folder and `.map` files by default. You will want to uncomment these lines if you are compiling these on the server; think continuous integration.


## Need more help?

* [Usage](usage.html) — Overview of the project contents.
<!-- * [FAQ](faq.html) — Frequently asked questions, along with their answers. -->

<!-- ### Markup -->

<!-- * [HTML](html.html) — A guide to the default HTML. -->

### Presentation

<!-- * [CSS](css.html) — A guide to the default CSS -->
* [Sass](sass.html) — A guide to the default Sass
* [The Choreographic Grid](grid.html) — A guide to the Kickoff's grid framework
<!-- * [Typography](typography.html) — A more in-depth guide to Kickoff's type styles -->

### Behaviour

* [JavaScript](js.html) — A guide to the default JavaScript.
* [Grunt](grunt.html) — A guide to using [Grunt.js](http://gruntjs.com) with Kickoff

TMW uses their own styleguide for Javascript, please read it [here](https://github.com/tmwagency/TMW-frontend-guidelines/blob/master/Front-End%20development%20guidelines.mdown#section-6)