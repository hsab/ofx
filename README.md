# OFX - OpenFrameworks Management Tool

Put this script into your OpenFrameworks root directory (the one that contains
"`addons`" directory) or define the `OF_ROOT` and/or `OF_ADDONS` environment variables
so they point to your OpenFrameworks root directory and/or your OpenFrameworks
addons directory.

## Usage

`ofx` / `ofx help`
* print this help

`ofx refresh`
* redownload addons list (otherwise it is downloaded just once)

`ofx list`
* list all available addons

`ofx listinstalled`
* list all installed addons

`ofx search TEXT`
* search for text in name and description of addons

`ofx category`
* list categories of addons

`ofx category NAME`
* list all addons in the category

`ofx owner`
* list all owners

`ofx owner NAME`
* list all addons belonging to owner

`ofx info NAME`
* show info about addon

`ofx install NAME`
* install addon

`ofx reinstall NAME`
* remove and install addon

`ofx upgrade NAME`
* upgrade addon (call git pull in its directory)

`ofx remove NAME`
* remove addon

## Authors

OFX Tool by:

* [Pavol Rusnak](http://gk2.sk/)

ofxAddons.com website by:

* [James George](http://www.jamesgeorge.org/)
* [Greg Borenstein](http://gregborenstein.com/)
* [James Hughes](http://www.virtualjames.com/)
