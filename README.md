# cicamore
Amire egynél több link mutat linkek száma szerint rendezve link+fájlnév:
**ls -l | egrep -v ^total | tr -s ' ' | cut -d' ' -f2,9 | sort -n | egrep -v "^1 "**
