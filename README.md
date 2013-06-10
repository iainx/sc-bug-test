sc-bug-test
===========

A bug in soundcloud or webkit

Steps to Reproduce
==================

Chrome or Webkit:

1. Load sc-test.html in a tab. There should be 3 players shown in the following
   order: Double Dagger - Heretic's Hymn, Jonathan Rado - Faces, CFC - Camera
2. Go to another website in the same tab
3. Press back. The widgets will reload. Sometimes they're not in the same order

Chrome:

1. Load sc-test.html in a tab.
2. Close tab
3. Press CTRL+Shift+T (reopen closed tab)
4. Page will reload in a page, but they load in the incorrect order.
