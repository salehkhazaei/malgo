## malgo
[![TravisCI Build Status](https://travis-ci.org/gen2brain/malgo.svg?branch=master)](https://travis-ci.org/gen2brain/malgo) 
[![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/eofqkk271yjd3s3g?svg=true)](https://ci.appveyor.com/project/gen2brain/malgo)
[![GoDoc](https://godoc.org/github.com/salehkhazaei/malgo?status.svg)](https://godoc.org/github.com/salehkhazaei/malgo) 
[![Go Report Card](https://goreportcard.com/badge/github.com/salehkhazaei/malgo?branch=master)](https://goreportcard.com/report/github.com/salehkhazaei/malgo) 
<!--[![Go Cover](http://gocover.io/_badge/github.com/salehkhazaei/malgo)](http://gocover.io/github.com/salehkhazaei/malgo)-->

Go bindings for [miniaudio](https://github.com/dr-soft/miniaudio) library.

Requires `cgo` but does not require linking to anything on the Windows/macOS and it links only `-ldl` on Linux/BSDs.

### Installation

    go get -u github.com/salehkhazaei/malgo

### Documentation

Documentation on [GoDoc](https://godoc.org/github.com/salehkhazaei/malgo). Also check [examples](https://github.com/salehkhazaei/malgo/tree/master/_examples).

### Platforms

* Windows (WASAPI, DirectSound, WinMM)
* Linux (PulseAudio, ALSA, JACK)
* FreeBSD/NetBSD/OpenBSD (OSS/audio(4)/sndio)
* macOS (CoreAudio)
* Android (OpenSL|ES, AAudio)
