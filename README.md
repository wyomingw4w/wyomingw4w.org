Wyoming Women for Women
=======================

_The website for Wyoming Women for Women_

**Available at https://www.wyomingw4w.org**

Requirements
------------

### Built with

* [jekyll](https://jekyllrb.com/)
* [minimal-mistake theme](https://mmistakes.github.io/minimal-mistakes/)

### Prerequisites

* [rbenv](https://github.com/rbenv/rbenv)

Setup
-----
1. `$ rbenv install`
2. `$ rbenv rehash`
3. `$ gem install bundler`
4. `$ bundle install`

Updating
--------
1. Update ruby:
   1. `rbenv install --list`
   2. Choose latest stable version
   3. Update `.ruby-version`
   4. `rbenv install`
   5. `rbenv rehash`
2. Update bundler: `bundle update --bundler`
3. Update main gems
   1. Lookup versions at https://rubygems.org/gems/
   2. Update each version in `Gemfile`
   3. `bundle install`
4. Update gem deps: `bundle update`
5. Test
6. Commit

Testing
-------

1. `$ bundle exec jekyll serve`
2. Visit http://localhost:4000/

Deploying
---------

1. `$ bundle exec jekyll build`
2. Copy files from `_site` to webserver
