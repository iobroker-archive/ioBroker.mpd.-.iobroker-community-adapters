![Logo](admin/mpd.png)
# ioBroker.mpd adapter

[![NPM version](https://img.shields.io/npm/v/iobroker.mpd.svg)](https://www.npmjs.com/package/iobroker.mpd)
[![Downloads](https://img.shields.io/npm/dm/iobroker.mpd.svg)](https://www.npmjs.com/package/iobroker.mpd)
[![Tests](http://img.shields.io/travis/instalator/ioBroker.mpd/master.svg)](https://travis-ci.org/instalator/ioBroker.mpd)

[![NPM](https://nodei.co/npm/iobroker.mpd.png?downloads=true)](https://nodei.co/npm/iobroker.mpd/)

Connect to a [music player daemon](http://musicpd.org) server, send commands,
emit events.

## Documentation

See also the [MPD Protocol Documentation](http://www.musicpd.org/doc/protocol/).


## Changelog

#### 0.1.0
* 22.12.2016 (instalator) change structure

#### 0.0.13
* 21.12.2016 (instalator) clearTag(), adding states - progressbar and mute

#### 0.0.12
* 19.12.2016 (instalator) add support sayit. add state addplay

#### 0.0.11
* 18.12.2016 (instalator) add tests

#### 0.0.10
* 15.12.2016 (instalator) add update status if play, to check whether the value has changed, fix error, fix different cmd

#### 0.0.3
* 14.12.2016 (instalator) fix send command
                          change functions parse
                          add function status mpd

#### 0.0.2
* 13.12.2016 (instalator) Add send command

#### 0.0.1
* 11.12.2016 (instalator) initial adapter


## License
The MIT License (MIT)

Copyright (c) 2016 instalator<vvvalt@mail.ru>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
