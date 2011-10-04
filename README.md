Fairbrix daemon - an experimental and fairly crude port of ArtForz's awesome CPU-friendly/GPU-hostile mining code to multicoin-exp
The result is a fairbrix "guiless" daemon that neatly complements that viewtifull Fairbrix propper with its GUI

Windows compile is currently messy on this one - it requires cc.exe which, in case it is for some reason not in your C:\MinGW32\bin can be produced by cloning and renaming gcc.exe (thanks google)

Linux compilation should proceed as per original bitcoin documentation.

DON'T FORGET TO PLACE fbx.conf into your APPDATA or default fairbrix folder (%APPDATA%\fairbrix on Win, ~/.fairbrix/ on Unixes)

