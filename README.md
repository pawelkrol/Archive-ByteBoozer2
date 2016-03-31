Archive-ByteBoozer2
===================

`Archive::ByteBoozer2` package provides a Perl interface to David Malmborg's [ByteBoozer 2.0](http://csdb.dk/release/?id=145031), a data cruncher for Commodore files written in C. The following operations are supported: crunching files, crunching files and making an executable with start address `$xxxx`, crunching files and relocating data to hex address `$xxxx`.

VERSION
-------

Version 0.02 (2016-03-24)

INSTALLATION
------------

To install this module type the following:

    perl Makefile.PL
    make
    make test
    make install

To build a distribution package type this:

    make dist

DOCUMENTATION
-------------

A comprehensive module documentation is available on [CPAN](http://search.cpan.org/~pawelkrol/Archive-ByteBoozer2/lib/Archive/ByteBoozer2.pm).

COPYRIGHT AND LICENCE
---------------------

ByteBoozer 2.0 cruncher/decruncher:

Copyright (C) 2016 David Malmborg.

Archive::ByteBoozer2 Perl interface:

Copyright (C) 2016 by Pawel Krol.

This library is free open source software; you can redistribute it and/or modify it under the same terms as Perl itself, either Perl version 5.8.6 or, at your option, any later version of Perl 5 you may have available.

PLEASE NOTE THAT IT COMES WITHOUT A WARRANTY OF ANY KIND!
