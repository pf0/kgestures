# Custom libinput gestures for Dell XPS 13 9370 with KDE Plasma as a desktop environment.


```bash
tmpId=$(qdbus --literal org.kde.KWin /Scripting  org.kde.kwin.Scripting.loadScript /home/pf0/kgesture/test.js) \
&& qdbus org.kde.KWin /$tmpId org.kde.kwin.Script.run && qdbus org.kde.KWin /$tmpId org.kde.kwin.Script.stop \ 
&& qdbus org.kde.KWin /Scripting  org.kde.kwin.Scripting.unloadScript /home/pf0/kgesture/test.js

```
