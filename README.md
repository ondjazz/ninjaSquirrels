980 Responsive
=============

Bartosz, Tor and Jonas loves sport...

Markup
-------

The grid uses the exact same markup as the fixed 980 grid.
gridRow with gridUnits span 1 to 10 and splits 2 to 5.

Mobile
------------

In order to "mobilize" the content, I've introduzed three new classes that are applied to the gridUnit: mobileFull, mobileSplit2 and mobileFlat. Class names subject to change :)


Breakpoints
------------

In order to marry what in reality is two different worlds, the fixed pixel perfect magazine-like "big edition", and the fluid content first "small edition", this grid serves only one major breakpoint at 640px. That's when the css stops listening to spans and splits, and the mobileClasses kicks in.

###All breakpoints:

Mobile scaling for readability: <240, 280, 320, 400, 480, =640.
Fluid grid: 641 to 767.
Fixed, scaled grid: 768 (tablet portrait), 820 (big screen half), 900 (prevent horiz scroll when using bookmarks bar etc), 1024 (tablet landscape and up)