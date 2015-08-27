---
title: "Start blogging"
layout: post
---

I used [Jekyll](http://jekyllrb.com/) to build this blog as that is what [GitHub recommends](https://pages.github.com/). For all those people who think that knowing [Ruby](https://www.ruby-lang.org/en/) is a necessity to deploy a blog using Jekyll, that is not the case. As a matter of fact I have never written a single line of code in Ruby till now. However the following tools come in handy when you are trying to install all the dependencies for Jekyll. I was often confused by Ruby terminologies like Bundler, Gems, RVM, Gemset, Rakefile etc. so this post is about sharing some of my discoveries while making this blog.

* [Rake](https://github.com/ruby/rake) and Rakefile: Rake is like Make for Ruby i.e. a software task management and build automation tool, and Rakefile is like Makefile i.e. a file written in Ruby syntax containing specifications for Rake command.
* [Gems](http://guides.rubygems.org/what-is-a-gem/): A format to package Ruby libraries and programs. Just like `.jar`s (Java Archives) for Java. There are `.rb` files with Ruby code, tests, documentation, `.gemspec` contains gem specification like name, version, description, authors etc., rakefiles inside a gem. There is a GemFile in most of the Ruby projects which contains list of all the gems that the project is dependent on.
* [Rubygems](https://github.com/rubygems/rubygems): It is Ruby's package manager, used to install gems.
* [Bundler](http://bundler.io/): More popular and better package manager which is not a part of Ruby. It itself is installed as a gem by doing `gem install bundler`. Bundler installs all gems automatically for your project by reading a Gemfile.
* [RVM](https://rvm.io/): Ruby Version Manager is a command-line-tool which lets you install and switch between multiple Ruby versions on a single machine.
* [Gemsets](https://rvm.io/gemsets): These are sets of Gems specific to some context(like a project) in RVM. This comes in handy when you have different applications, each with it's own set of Gems and want to keep them separate.

There are some pseudo alternatives (as they are built upon Jekyll as well) to Jekyll like [Octopress](http://octopress.org/) and [Barry Clark's jekyll-now](https://github.com/barryclark/jekyll-now) also. These are basically just someone else's Jekyll blog which you can fork and just start publishing content without worrying about the design and aesthetic aspects. So these are good alternatives if you don't want to customize the look of your blog and just focus on writing. I started with Octopress but then switched back to starting from scratch using Jekyll as that seemed more easy. Jekyll is pretty easy to learn and they have a fairly comprehensive [documentation](http://jekyllrb.com/docs/home/) which I recommend everyone to read if you will be deploying a Jekyll blog directly or indirectly.

If you don't want to use Jekyll then there are other cool blog generators out there like [Ghost](https://ghost.org/) (Javascript) and some obvious no-coding-required once like [Wordpress](https://wordpress.org/) and [Weebly](http://www.weebly.com/features/#!/blogging). More static site generators can be found [here](https://www.staticgen.com/).

The design of this blog is inspired from [Julia Evan's](http://jvns.ca/) blog. I also like her [Python Pandas Cookbook](https://github.com/jvns/pandas-cookbook).

Thanks to Jekyll and GitHub people. You guys are awesome :)
