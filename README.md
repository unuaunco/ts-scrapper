#Readme for Github project API

Script for work with m8u8 file, to get .ts from url and build it to mp4

Require ffmpeg binary


Scripts:

`scrapper.py`
```
usage: scrapper.py [-h] [-m M8U8_URL] [-f FFMPEG_PATH]

optional arguments:
  -h, --help            show this help message and exit
  -m M8U8_URL, --m8u8-url M8U8_URL
                        Path to the m8u8 playlist file
  -f FFMPEG_PATH, --ffmpeg-path FFMPEG_PATH
                        Path to the ffmpeg binary
```

Result: video.ts and video.mp4 in folder with script

Example:

> python.exe .\scrapper.py -u "https://hdm-streaming-otfp.hearst.io/198d52d2-9af0-4458-a8be-a996cf3280ea/video_rover_16x9_1080p_hd_1537461620_21981.m3u8" -f "..\ffmpeg-20190329-9dece05-win64-static\bin\ffmpeg.exe"

---

Exit Error codes:

In development ...