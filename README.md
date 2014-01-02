GnuCash QIF Import
------------------

[GnuCash][GnuCash] Python helper script to import transactions from [QIF][QIF] text files into GnuCash .gnucash file.

Main use case for myself was automating the import of QIF files generated by [GnuCash Mobile][GnuCash Mobile] Android app into my desktop GnuCash application.


Prerequisites
==============

* Python 2.7+
* GnuCash 2.4+
* GnuCash Python Bindings

Getting Started
===============

For Ubuntu 13.04:

    sudo apt-get install gnucash python-gnucash
    ./import.py -v -f examples/accounts.gnucash examples/expenses.qif

[GnuCash]:        http://www.gnucash.org
[QIF]:            http://en.wikipedia.org/wiki/Quicken_Interchange_Format
[GnuCash Mobile]: https://play.google.com/store/apps/details?id=org.gnucash.android&hl=en
