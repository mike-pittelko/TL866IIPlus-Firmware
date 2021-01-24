# TL866IIPlus-Firmware
Copy of TL866 II Plus firmware from xgecu for use with linux/osx.  Does not include windows tools, etc.

This was very slow to download from xgecu.  If you are not using their software (for example, minipro on a mac or linux) you will likely need this file to update your programmer. 

You can always get the latest offical package from here: http://forums.xgecu.com/viewthread.php?tid=20&page=1&extra=#pid23

To get the update from their distribution, download the .rar file (it will take a long time!), unrar (for example, using 7z, or Keka), then extract the enclosed .exe file (it is a self-compressed executable).  Inside you will find a file called "updateII.dat" - this is the update file for the TL866 II Plus, and is the file stashed in this repo.


Not that this file is for the TL866 II Plus ONLY


To udpate the programmer via minipro is pretty easy.

     > minipro -t
       (lists test information for the programmer, and the current firmware version)
     > minipro -F <name of update file>
       (shows programming status)

You're done.
