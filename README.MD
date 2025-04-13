 # PGCBMP                          
Originally by John Elliott, 13 November, 2004.
Posted to github and subsequent modifications by trguhq, 2025 and on.

This is an example program which can be used to experiment with IBM's
Professional Graphics Controller. PGCBMP loads and displays 256-colour .BMP
files in the native 640x480 mode.

Syntax is:
```PGCBMP <bmpfile>```

The PGC will be put in native mode and the bitmap will be displayed. The 
image will remain onscreen until you press ESCAPE; then the screen will 
switch back to CGA mode and the program will quit. 

To abort display before the picture has finished loading, press ESCAPE once 
(to stop loading) and again (to return to DOS). 

Note that this program was written more as programming example 
than as a comprehensive utility. So error handling and ease of use have
been rather neglected.                        
