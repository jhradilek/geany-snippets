# Geany Snippets

## Description

The **geany-snippets** repository provides a collection of code snippets for **Geany**. In particular, it provides snippets for the following file types: 

* **docbook_snippets.conf** — Snippets for the DocBook XML language according to [DocBook: The Definitive Guide, version 2.0.17](http://www.docbook.org/tdg/).

* **mallard_snippets.conf** — Snippets for the Mallard XML language according to [Mallard 1.0 DRAFT (as of 2013-02-11)](http://projectmallard.org/1.0/index.html).

## Installation

To install snippets for a particular file type, change to the directory with your local copy of this repository, and copy the contents of the relevant file to the `$HOME/.config/geany/snippets.conf` file:

    cat <filetype>_snippets.conf >> ~/.config/geany/snippets.conf

For example, to install the snippets for the DocBook XML language, type:

    cat docbook_snippets.conf >> ~/.config/geany/snippets.conf

The snippets are loaded automatically the next time you start the editor.

## Copyright

Copyright © 2011, 2013 Jaromir Hradilek

This program is free software; see the source for copying conditions. It is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
