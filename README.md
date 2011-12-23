steamsale.py
============

A Python script for retrieving your Steam wishlist.

It can be combined with a crontab and send notifications if there are any items
in your wishlist that are currently on sale.

Usage
=====
    $ python steamsale.py
    usage: steamsale.py [OPTIONS] steam_id
     -h, --help         Display usage
     -s, --sale         Show only items that are on sale
     -c, --colors       Use colors in output

You'll need your Steam ID from the wishlist URL:

    http://steamcommunity.com/profiles/[this_one]/wishlist

Dependencies
============

* requests - http://docs.python-requests.org
* BeautifulSoup - http://www.crummy.com/software/BeautifulSoup
* termcolor - http://pypi.python.org/pypi/termcolor

All of them can be installed through pip

    pip install requests BeautifulSoup termcolor

..some of them are in apt too, if that's your thing

    aptitude install python-requests python-beautifulsoup