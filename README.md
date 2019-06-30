cpub
====

ncurses based epub reader for the command line.
Based on https://github.com/rupa/epub

![GIF](https://thumbs.gfycat.com/OblongSaneChimneyswift-size_restricted.gif)

Install
-------

```
usage: cpub <filename>
```

Copy the `cpub` binary to any directory which is in `$PATH`, preferably
`$HOME/bin`.


Controls
--------

 - **q** - quit

### Table of contents

 - **j/k** - up/down navigation of table of contents
 - **o**   - open chapter

### Chapter

 - **j** - next page in chapter (or next chapter if on last page)
 - **k** - prev page in chapter (or prev chapter if on first page)
 - **b** - back to table of contents
