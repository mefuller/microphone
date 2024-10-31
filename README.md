# Microphone [![GoDoc](https://godoc.org/github.com/mefuller/microphone?status.svg)](https://godoc.org/github.com/mefuller/microphone) [![Go Report Card](https://goreportcard.com/badge/github.com/mefuller/microphone)](https://goreportcard.com/report/github.com/mefuller/microphone)

Microphone is a small library that takes [this Go PortAudio library](https://github.com/gordonklaus/portaudio)
and wraps its microphone stream in a beep.StreamCloser
so that it can be used with everything else in the [Beep library](https://github.com/gopxl/beep).

```bash
go get -u github.com/mefuller/microphone
```

## Installation
This package requires that you have the PortAudio development headers and libraries installed.
On Ubuntu this can be done using:
```sh
apt-get install portaudio19-dev
```
On Fedora this can be done using:
```sh
dnf install portaudio-devel
```
See [the PortAudio library](https://github.com/gordonklaus/portaudio) for more information.

## License

[MIT](https://github.com/mefuller/microphone/blob/master/LICENSE)
