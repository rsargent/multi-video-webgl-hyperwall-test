To run this in chrome with file: URL, you need to start chrome with these args:

    --video-threads=8 --allow-file-access-from-files

E.g. if you're running on a mac, type:

    /Applications/Google\ Chrome.app/Contents/MacOS/Google\ Chrome --video-threads=8 --allow-file-access-from-files

Watch for smooth playback.  Also consider turning on FPS meter in chrome://flags.  If you see stutters but the meter stays at 60 FPS, perhaps that's a driver or OS problem?
