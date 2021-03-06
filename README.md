[Bugzilla Lite](http://bzlite.com/) - Bugzilla Lite
===================================================

Bugzilla Lite is a bugzilla client designed to work well on mobile devices.


Running Bugzilla Lite
---------------------

From a local checkout of the bzlite repository:

    $ npm install
    $ npm start

A local copy of Bugzilla will now be running at http://127.0.0.1:3000.
There are a few options you can provide to startup.

 * TEST=1 - Run against https://bugzilla-dev.allizom.org/
 * VERSION=1 - An ultra minimal version that only allows bug filing
 * PORT=1234 - Run on a custom port


Running Bugzilla Lite Tests
---------------------------

   $ npm test


Contributing to Bugzilla Lite
-----------------------------

You can find bugs in the [`Bugzilla Lite` Component](https://bugzilla.mozilla.org/buglist.cgi?component=Bugzilla%20Lite&product=Firefox%20OS&bug_status=__open__&list_id=12133703).
