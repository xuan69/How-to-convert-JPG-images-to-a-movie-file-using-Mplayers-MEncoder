# How-to-convert-JPG-images-to-a-movie-file-using-Mplayers-MEncoder
Here’s a command line to convert a folder with jpg’s into a mp4 using MEncoder

mencoder mf://*.jpg -mf fps=25 -o output.avi -ovc lavc -lavcopts vcodec=mpeg4

MEncoder is part of MPlayer, download from [Sourceforge](http://sourceforge.net/projects/mplayer-win32/)

