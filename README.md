# About
This project is forked from https://github.com/qt/qtwebengine-chromium.

## Build
First install third party packages:
```shell
               bison,
               chrpath,
               closure-compiler,
               debhelper (>= 10),
               flex,
               git,
               gperf,
               khronos-api,
               libasound2-dev [linux-any],
               libavcodec-dev (>= 7:3.1.1),
               libavformat-dev (>= 7:3.1.1),
               libavutil-dev (>= 7:3.1.1),
               libcap-dev [linux-any],
               libdbus-1-dev,
               libegl1-mesa-dev,
               libevent-dev,
               libflac-dev,
               libfontconfig1-dev,
               libgl1-mesa-dev [!armel !armhf] | libgl-dev [!armel !armhf],
               libgl1-mesa-dri,
               libgles2-mesa-dev [armel armhf] | libgles2-dev [armel armhf],
               libglib2.0-dev,
               libglu1-mesa-dev [!armel !armhf] | libglu-dev [!armel !armhf],
               libgstreamer-plugins-base1.0-dev,
               libgstreamer1.0-dev,
               libharfbuzz-dev,
               libicu-dev,
               libjpeg-dev,
               libjsoncpp-dev,
               liblcms2-dev,
               libminizip-dev,
               libnss3-dev,
               libopus-dev,
               libpci-dev,
               libpng-dev,
               libprotobuf-dev,
               libpulse-dev,
               libqt5opengl5-dev (>= 5.6.0~),
               libqt5webchannel5-dev (>= 5.6.0~),
               libre2-dev,
               libsnappy-dev,
               libsqlite3-dev,
               libsrtp-dev,
               libusb-1.0-0-dev,
               libvpx-dev,
               libwebp-dev,
               libxcomposite-dev,
               libxcursor-dev,
               libxml2-dev,
               libxnvctrl-dev,
               libxrandr-dev,
               libxrender-dev,
               libxslt1-dev,
               libxss-dev,
               libxtst-dev,
               mesa-common-dev,
               ninja-build,
               pkg-config,
               pkg-kde-tools,
               protobuf-compiler,
               python,
               qtbase5-private-dev (>= 5.6.0~),
               qtdeclarative5-private-dev (>= 5.6.0~),
               qtpositioning5-dev,
               qttools5-dev,
               re2c,
               ruby,
               xauth,
               xvfb,
               yasm [amd64 i386],
```

Then get submodule:
```shell
git submodule update --init
```
