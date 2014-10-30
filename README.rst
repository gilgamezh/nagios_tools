

check_graphite_data
===================

Simple Python script to check a Graphite metric forked from one written at Etsy -->  https://github.com/etsy/nagios_tools


```
usage: check_graphite_data [-h] --warning WARNING --critical CRITICAL
                           [--reverse] [--secs SECS]
                           url

Alert on data, based on number from Graphite.

positional arguments:
  url                   Graphite metric URL

optional arguments:
  -h, --help            show this help message and exit
  --warning WARNING, -w WARNING
                        Warning threshold
  --critical CRITICAL, -c CRITICAL
                        Critical threshold
  --reverse, -r         Reverse - Alert when the value is
                        UNDERwarning/critical instead of OVER
  --secs SECS, -s SECS  Average over the last N seconds of data
```
