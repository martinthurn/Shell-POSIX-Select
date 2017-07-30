Notes to author(s) of this module
---------------------------------

Instructions
------------

When it's time to increment the version number, you must do the following:

1. BEFORE changing the value of $VERSION in Select.pm, make sure all tests pass
2. Increment the value of $VERSION in Select.pm
3. Run test.pl with environment variable "Shell_POSIX_Select_reference" set.  This will rebuild the reference data and run all tests.


History
-------
This module Shell::POSIX::Select was written by Tim Maher,
but he retired around 2015 and disappeared from the Internet.
Martin Thurn (mthurn@cpan.org) took over maintenance ealy in 2017.