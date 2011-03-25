Date From-To
============

Date from-to is supposed to be a simple class that allows you display a date in a From/To format. 

What this means is by providing a start/end date, you can have an output such as:

*March 23-26, 2011*

Take note of the 23-26 date which is what we are looking for. So dates don't end up like:

*March 23, 2011 - March 26, 2011*

## Examples

**Input** 01-21-1986, 01-21-1986  --- **Output** January 21, 1986
**Input** 01-21-1986, 01-24-1986  --- **Output** January 21 - 24, 1986
**Input** 01-21-1986, 02-21-1986  --- **Output** January 21 - February 21, 1986
**Input** 01-21-1986, 01-21-1987  --- **Output** January 21, 1986 - 1987