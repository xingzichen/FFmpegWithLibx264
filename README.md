# FFmpegWithLibx264

FFmpeg with libx264 build for iOS

Test with :
* x264-snapshot-20170408-2245
* FFmpeg 3.2.4
* Xcode 8.3.1

## Install every thing we need
1. Xcode8
2. in terminal $xcode-select --install
3. install yasm, automake, libtool with 'brew install'
4. put gas-preprocessor.pl to /usr/local/bin/ , then $chmod +x /usr/local/bin/gas-preprocessor.pl

## How to build

1. run build_x264.sh in the folder x264.
2. git checkout n3.2.4 for ffmpeg.
3. run build_ffmpeg.sh in the folder ffmpeg.

