# CDAdl - CDA downloader
This is CDA downloader, it allows user to easly get access to source of any (currently only public) video on cda.pl, it allows you to save link to file (along with it's name), download it directly and also allows you to download/list whole folder.

# Requirements
It was written in python 3.9.5 so I strongly encourage you to use this version, it also (at least for now) requires firefox and geckodriver in PATH. 

Python libraries are included in requirements.txt file, you can install them using `pip install -r requirements.txt`.

# Usage
~~`python cdadl.py <cda link to video/folder>` will by default get source video/s link/s from link and save it to a file.~~

~~To download video or folder you can use `-d` flag, after it finished gathering links it saves them to temporary txt file and starts downloading them using internal downloader (It's very basic, I have in plan adding support for external downloaders like aria2c or wget, also I removed aria2c just for convenience)~~

~~You can get more info about it by using `-h` or `--help`flag.~~

New version now has functional GUI, it lacks couple of functions but it's first version and I will keep updating it. I made binary for windows in releases (default folder/file path is bugged). I haven't made binary for linux for now because I didn't thought it was necesarry, y'all can use python alright, I know because I use it myself.
