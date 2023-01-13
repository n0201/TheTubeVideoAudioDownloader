# TubeVideoAudioDownloader
A small python based programm which is able to download Tube video and audio files.
## Description

A small python based programm which is able to download Tube video and audio files.

### Dependencies

Windows 10/11

### Screenshots

![Screenshot 2023-01-09 170823](https://user-images.githubusercontent.com/87095139/211354239-612c07ed-3b3e-4863-8dfe-fe6e8b2e23e8.png)
![Screenshot 2023-01-09 170852](https://user-images.githubusercontent.com/87095139/211354294-ecfa8464-b50f-4df4-bb60-afb5d71ff180.png)


### Executing program

* extract the program.zip file
* open main.exe
* choose between Audio and Video download
* paste the YouTube link into the entry
* press download
* the file will appear in the folder

## Authors

ex. n0201 

ex. [@Conrad1406](https://github.com/Conrad1406)

## About the program
the program was written in Python using [Pytube](https://github.com/pytube/pytube), [customtkinter](https://github.com/TomSchimansky/CustomTkinter), [winotify](https://github.com/versa-syahptr/winotify), [request](https://github.com/psf/requests) and [moviepy](https://github.com/Zulko/moviepy) and was converted to an easy usable program with [auto-py-to-exe](https://github.com/brentvollebregt/auto-py-to-exe)

Program will freeze while clicking on "Download", "get resolutions BETA VERY VERY slow" and on "Download video". This is not easy fixable and is normal. The biggest freeze will be when you download a video with the desired resolution as youtube will send a video and audio signal seperated which has to be merged whith moviepy. I might find a fix and "VERY VERY slow" might change to "Very slow" ;D 
