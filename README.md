nagios-check_sa
===============

Nagios plugin that uses sadf from sysstat package to check counters

v0.22

* added parameters to sadf to limit the number of records displayed, 2 days of data took 8 seconds now down to 0.14 seconds
* parameters sent to sadf are based on -m check_sa.pl parameter

This check is from here https://github.com/jgoldschrafe/check_sa.git with some optimizations

