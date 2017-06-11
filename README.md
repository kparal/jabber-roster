jabber-roster
=============

[![No Maintenance Intended](http://unmaintained.tech/badge.svg)](http://unmaintained.tech/)

A simple Python tool for listing your Jabber roster contacts. You can use it to easily backup list of your buddies.

This program is no longer maintained. If you want to work on this program, please fork. If you have some cool new features, contact me, and I'll redirect visitors to you.

Running
=======

You can run the tool directly simply by:

    $ ./jabber_roster.py

or by:

    $ python jabber_roster.py

(use `--help` option of course if you don't know this tool yet)


Installation
============

You can install this tool using [distutils][], [setuptools][] or [pip][] and have it in your PATH that way.

The recommended way:

    # easy_install -U jabber-roster

That will find, download and install the latest available version of jabber-roster.

[distutils]:  http://docs.python.org/install/index.html#install-index
[setuptools]: http://peak.telecommunity.com/DevCenter/setuptools
[pip]:        http://pip.openplans.org/


Dependencies
============

If you haven't used the recommended way of installation, you might need to manually install some dependencies:

 * xmpppy: <http://xmpppy.sourceforge.net/> (usually available as `python-xmpp` package)

**PLEASE NOTE**: Currently it is necessary to install `xmpppy` from a forked
project <https://github.com/ArchipelProject/xmpppy> instead of the official
upstream project, because it does not contain
[a fix for latest SSL changes](https://github.com/ArchipelProject/xmpppy/commit/c61c64972b12d3bfeca7200a18965886cbf51263).
Once it is updated (if it is), you can go back to using original `xmpppy`.


License
=======

This program is a free software, licensed under GNU AGPL 3+. See `LICENSE` file.


Donations
=========

If you like this program you can [Flattr it](https://flattr.com/thing/78799/jabber-roster).

[![](http://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/thing/78799/jabber-roster)


Contact
=======

Visit program homepage at: <https://github.com/kparal/jabber-roster>

Please report all bugs to the [issue tracker](https://github.com/kparal/jabber-roster/issues), but don't request new features unless you have a patch for it. This is a small personal project and I don't plan to spend much more time on it. I will gladly merge your patches if they look reasonable.
