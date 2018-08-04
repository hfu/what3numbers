# what3numbers
[z, x, y] as a space partitioning code

## Background
I want to give a catchy name for the [slippy map tilenames](https://wiki.openstreetmap.org/wiki/Slippy_map_tilenames) tile number.

## Specification for what3numbers
A what3numbers is the tile number in slippy map tilenames concatenated by hyphens('-') in the [z, x, y] order, e.g., 2-3-1.

## Existing applications of what3numbers
- what3numbers is in [module-spec](https://github.com/hfu/module-spec). The module-spec is used in producing vector tile datasets.

## Web site specification
- To be developed at https://hfu.github.io/what3numbers
- http://hfu.github.io/what3numbers?2-3-1 shall show the extent of what3numbers 2-3-1.

## Technical documentation for the web site
- [tilebelt](https://github.com/mapbox/tilebelt) shall be used.

## See also
- [what2numbers](https://what2numbers.org) is a great way to identify an exact location, rather than a partition of space. 

## [License](LICENSE)
All of works in this repository are under the Unlicense.
