jQuery.Fontspacing
===

About
---
Some multi-byte characters don't display with the correct width in older browsers.  For example, the (glottal stop character, ʔ)[http://en.wikipedia.org/wiki/Glottal_stop] renders with zero-width in 2.x branch Android browsers.  This plugin corrects the width of these characters by exhaustivly searching for them, when needed, and increasing the space of the corresponding elements as needed.

Requires
---
jQuery

Usage
---
$("span.text-sections").fontspacing();

Author
---
Peter Snyder <snyderp@gmail.com>
