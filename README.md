Description
===========
[RSpec](http://rspec.info/) is a BDD (Behavioral-Driven Development) testing framework for Ruby. This package adds support to Sublime Text 2 for testing Ruby applications with RSpec.

Package Installation
====================
### Mac OSX
    cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
    git clone git://github.com/SublimeText/RSpec.git
### Linux
    cd ~/.config/sublime-text-2/Packages
    git clone git://github.com/SublimeText/RSpec.git
### Windows
    cd "%appdata%\Sublime Text 2\Packages"
    git clone git://github.com/SublimeText/RSpec.git

When you launch Sublime Text 2, it will pick up the contents of this package so that you can consume the goodness that it provides.

Features
========
* RSpec.sublime-build for executing unit tests for the active module via the S2 *Build* command
    * You must assign the builder for your project to 'Ceedling'
