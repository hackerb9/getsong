# getsong
Wrapper for yt-dlp that makes searching and downloading songs easier

* Handles multiple arguments (including embedded spaces) correctly. 
* Uses youtube.com URL, instead of ytsearch:
* Allows `-c` to restrict search to videos with closed captions (manually generated lyrics/subtitles).
*  Can read search terms from a file, downloading one song per line.
* If `xsel` is installed, will search for whatever words are currently highlighted by the mouse cursor and download that song.
* Can download videos instead by changing the script's name: `ln -s getsong getvideo`

## Installation

It's just a bash script. Download it, make it executable, and put it in your PATH. 

```bash
wget https://raw.githubusercontent.com/hackerb9/getsong/main/getsong
chmod +x getsong
sudo mv getsong /usr/local/bin/
```
