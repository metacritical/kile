Kile is a Programmers Editor 
============================

Kile is a small text editor forked from Kilo which is only 1K lines of code (counted with cloc).

A screencast for Kilo is available here: https://asciinema.org/a/90r2i9bq8po03nazhqtsifksb

Usage: kile `<filename>`

Keys:

    CTRL-S: Save
    CTRL-Q: Quit
    CTRL-F: Find string in file (ESC to exit search, arrows to navigate)

Kilo does not depend on any library (not even curses). It uses fairly standard
VT100 (and similar terminals) escape sequences. Kile uses other libraries to build further.

Kilo project is in alpha stage and was written in just a few hours taking code 
from antirez's other two projects, load81 and linenoise thus by mechanism of inheritance
Kile has some of these features aswell. But these may not remain so for long.

Kilo was written by Salvatore Sanfilippo aka antirez and is released
under the BSD 2 clause license.

Kile is being written by Pankaj Doharey and continues to use the same BSD license 
as the original Kilo.

Kile is a derivative work based on Kilo and uses other OSS projects. 
All dependencies are shipped with their respective Licenses and are applicable to the parts of
this software. 
