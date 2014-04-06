# OctoTadl #

My first [Octopress](http://Octopress.org) Theme powering [taufderl.de](http://taufderl.de)

Live theme preview available at .

Based on the theme [MediumFox](https://github.com/sevenadrian/MediumFox) by [AdrianArtiles.com](http://AdrianArtiles.com).

## Installation ##

````
$ cd yourOctopress
$ git submodule add https://github.com/taufderl/octotadl .themes/octotadl
$ git submodule update --init
$ rake install['octotadl']
$ rake generate
````

### Grab the latest updates ###

````
$ cd yourOctopress
$ git submodule update
$ rake generate
# regenerate, make changes, etc...
````

## Alternate Installation Without Git Submodule ##
````
$ cd yourOctopress
$ git clone https://github.com/taufderl/octotadl .themes/octotadl
$ rake install['ototadl']
$ rake generate
````
