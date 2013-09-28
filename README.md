# RVM Cheat Sheet
===============

## To create a new gemset with Ruby 2 and Rails 4

`rvm use ruby-2.0.0-p247@rails4 --create`

`gem install rails --version=4.0.0 --no-rdoc --no-ri`



## Then to use this gemset in a new command line window

`rvm use ruby-2.0.0-p247@rails4`

======

##To make this your default gemset

`rvm use ruby-2.0.0-p247@rails4 --default`

Quit your command line - and now it should be the default gemset

## Other commands

`rvm list` Lists your rubies and shows your default and current

`rvm gemset list` Lists your gemsets and shows your default and current
