notmuch2gmvault
===============

A small tool to convert a notmuch database to a [gmvault](http://gmvault.org/)
backup.  Useful if you want to import your notmuch mail store into GMail.

Howto (first make sure ~/gmvault-db is empty):

    $ ./notmuch2gmvault
    $ gmvault restore myaccount@gmail.com

And all your mail are in your GMail account, with tags/labels, unread, starred,
and inbox status preserved.  Spam and deleted messages are not imported as they
are not supported by gmvault.
