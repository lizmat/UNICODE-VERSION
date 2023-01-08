[![Actions Status](https://github.com/lizmat/UNICODE-VERSION/actions/workflows/test.yml/badge.svg)](https://github.com/lizmat/UNICODE-VERSION/actions)

NAME
====

UNICODE-VERSION - Provide $?UNICODE-VERSION for older Raku versions

SYNOPSIS
========

```raku
use UNICODE::VERSION;
```

DESCRIPTION
===========

UNICODE-VERSION checks the unicode database at compile time for certain marker codepoints that got added at certain unicode versions and exports a `%?UNICODE-VERSION` `Version` constant that indicates the version of Unicode that is currently being supported, as determined by those codepoints.

Algorithm suggested by Stephen Schulze

AUTHOR
======

Elizabeth Mattijsen <liz@raku.rocks>

Source can be located at: https://github.com/lizmat/UNICODE-VERSION . Comments and Pull Requests are welcome.

If you like this module, or what I’m doing more generally, committing to a [small sponsorship](https://github.com/sponsors/lizmat/) would mean a great deal to me!

COPYRIGHT AND LICENSE
=====================

Copyright 2023 Elizabeth Mattijsen

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

