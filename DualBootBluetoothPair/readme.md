# Bluetooth-sync

This bash script tries to sync bluetooth pair between Windows and Linux

## WARNING

This script is intended to be used with root privileges, please read the code carefully before using.

Also, take note of the path the command `reged` is using, because if it is wrong it will not be able to find your devices.
You can use command `reged -e SYSTEM` on `Windows/System32/config` and navigate using `ls` and `cd` to see if the path is right. 

Another thing is the `00:05:16:5C:2A:32` towards the end of the script. This is my pc bluetooth address, so you need to change to yours.


## how to use

After checking the above make sure that you have your bluetooth device paired on both systems, and that Windows was the last system to be paired. 
After that just execute the script using `sudo ./bluetooth-sync` and done.



### extra info

I'm probabbly gonna work on this script a bit more to make it fail safe at some point.
