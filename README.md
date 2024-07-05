# down_on_spot-packages
Debian bookworm packages for down_on_spot  
  
A Spotify downloader written in Rust  
⭐ Features  
✅ Actually downloads from Spotify, free and premium  
✅ Chose between 96, 160, 256 and 320 kbit/s (free users can't exceed 160kbit/s)  
✅ Download tracks, playlists, albums and artists  
✅ Multi-threaded  
✅ Search for tracks  
✅ Download MP3 and original OGG files  
✅ Metadata tagging  
✅ Simple CLI interface  
Note:Free Spotify users can not exceed 160kbit/s. Change the quality setting in the settings.json file to Q160 or lower. If you want to download 256 or 320kbit/s, you need to use a premium account.  

https://github.com/oSumAtrIX/DownOnSpot  
+-------------------------------------------------  

I builded these packages because they are not in debian 12 repository.  
x64,i386 & armhf packages provided.  
  
# installation:  
  
download appropriate package, and do (for example for 32bits package):  
  
```
sudo apt install ./down_on_spot-0.3.0_i386.deb
```
(or install with graphical .deb installer if you have one, for example QSI installer for q4os: left click the .deb, then 'open with' and choose QSI installer)  

# Usage:  
Create a new application on the Spotify developer dashboard
  
Run DownOnSpot:  
```
$ down_on_spot  
```
You'll get:  
Settings could not be loaded because of the following error: IO: NotFound No such file or directory. (os error 2)...  
..but default settings have been created successfully. Edit them and run the program again.  
Edit the settings.json file  
  
The settings.json file is located in the following directories:  
~/.config/down_on_spot/settings.json  
or (for trinity DE)  
~/.configtde/down_on_spot/settings.json  
  
++ more info on : https://github.com/oSumAtrIX/DownOnSpot  
  
  
+------------------------------+  
