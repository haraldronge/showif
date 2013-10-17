====== ShowIf Plugin for DokuWiki ======

Shows text only if all of some conditions are true.
Lazy hiding based on plugin nodisp from Myron Turner.

Syntax is \<showif [condition1], [condition2], ...\>[text]\</showif\>

Supported conditions are:

1. isloggedin
2. isnotloggedin
3. mayonlyread
4. mayatleastread
5. mayedit
6. isadmin

Administrators will always see everything except mayonlyread.
Not all combinations are useful ;-)

(c) 2013 by Harald Ronge <harald[at]turtur.nl>
See COPYING for license info.
