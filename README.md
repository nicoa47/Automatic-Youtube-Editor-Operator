# Browser based Youtube stream cutter

*Using Selenium to automatically operate the Youtube video editor to remove small breaks.* [WIP]

How often did you host a long livestream via Youtube while working on a project,
only to find that it is full of small, scattered thinking breaks and you cannot download
the video with highest data quality to efficiently edit it.
Well, it happened to me once and might again, so here is a small tool.

Breaks to cut out are identified via audio amplitude.

TODOs:
- find out if selenium can easily operate on the youtube editor
	- else, find lower level solution (control of mouse and keyboards)
	- then, figure out ways to automatically find coordinate positions of editor elements
- implement basic solution
- add features for cross-browser capability etc
