# LibMediaPlayer
An android media player library based on ijkplayer

[![Build Status](https://travis-ci.org/xdtianyu/LibMediaPlayer.svg?branch=master)](https://travis-ci.org/xdtianyu/LibMediaPlayer)
[![JAR](https://img.shields.io/maven-central/v/org.xdty.media/mediaplayer.svg)](http://central.maven.org/maven2/org/xdty/media/mediaplayer/)
[ ![Download](https://api.bintray.com/packages/xdtianyu/maven/mediaplayer/images/download.svg) ](https://bintray.com/xdtianyu/maven/mediaplayer/_latestVersion)

## Download

Grab via gradle

```
dependencies {
    compile 'org.xdty.media:mediaplayer:0.0.1'
}
```

or maven

```
<dependency>
  <groupId>org.xdty.media</groupId>
  <artifactId>mediaplayer</artifactId>
  <version>0.0.1</version>
  <type>aar</type>
</dependency>
```

or JAR from [maven central](http://central.maven.org/maven2/org/xdty/media/mediaplayer/)

## Usage

```
PlayerActivity.intentTo(this,
        "YOUR_MEDIA_URI",
        "YOUR_TITLE",
        ActivityInfo.SCREEN_ORIENTATION_LANDSCAPE);
```

For more details, see [example](https://github.com/xdtianyu/LibMediaPlayer/tree/master/example)

## Using your own jkplayer-armv7a builds

Put *.so files in your module's directory `app/src/main/jniLibs/armeabi-v7a`, then clean project and build again.

