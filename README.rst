Random Scripts
==============

This is just some scripts I've written, documented pretty well I think.

vimsp
-----

I use split-windows in vim a lot so I wrote this to make one call to vimsp.py with the windows in the positions I want them and they'll be there. Called like so:

::

> vimsp.py c1r1 c2r1 / c1r2
> vimsp.py c1r1 c2r1 / c1r2 c2r2
> vimsp.py c1r1 / c1r2


The final layouts look like so:

::

|====|====|
|    |    |
|====|====|
|         |
|=========|

::

|====|====|
|    |    |
|====|====|
|    |    |
|====|====|

::

|=========|
|         |
|=========|
|         |
|=========|
