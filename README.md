<h1 align="center">
  <a href="https://mpv.io/">
    <img src="https://i.imgur.com/qQFg0aI.png" alt="mpv" width="200">
  </a>
  <br>mpv.js<br><br>
</h1>

<h4 align="center">
  All format embeddable player for Electron/NW.js applications.
  <br>Powered by marvelous <a href="https://mpv.io/">mpv</a>.
</h4>

<p align="center">
  <a href="https://travis-ci.org/Kagami/mpv.js">
    <img src="https://img.shields.io/travis/Kagami/mpv.js.svg" alt="Travis">
  </a>
  <a href="https://npmjs.org/package/mpv.js">
    <img src="https://img.shields.io/npm/v/mpv.js.svg" alt="NPM">
  </a>
</p>

## Get libmpv

In order to try mpv.js you need to install mpv library first.

* Windows: download [mpv-dev](https://mpv.srsfckn.biz/mpv-dev-latest.7z), unpack, put corresponding `mpv-1.dll` to `C:\Windows\system32`
* macOS: `brew install mpv`
* Linux: `apt-get install libmpv1 libavformat-dev`

## Example

![](https://i.imgur.com/tLFkATs.png)
[Simple Electron application on Angular](https://github.com/pavladan/mpv.js-on-angular)


[Simple Electron application on React](https://github.com/pavladan/mpv.js-on-react) 

## Usage

### Add npm package

```bash
npm install mpv.js-vanilla --save
```

Package includes prebuilt binaries for all major platforms so no need to setup compilers. 

### See also

* [mpv properties documentation](https://mpv.io/manual/master/#property-list)
* [mpv commands documentation](https://mpv.io/manual/master/#list-of-input-commands)
* [ReactMPV source](index.js) with JSDoc API comments
* [example player source](example/renderer.js) for a more advanced usage

## Library connection

In order for mpv.js-vanilla to work, the path to the mpv library files must be passed to the getPluginEntry function. [MacOS](mpv/mac/) | [Windows](mpv/win/)

## License

mpv.js is licensed under [CC0](COPYING) itself. However if you use GPL build of libmpv (e.g. lachs0r builds) your application might violate GPL dynamic linking restrictions. LGPL build should be safe, see [mpv copyright](https://github.com/mpv-player/mpv/blob/master/Copyright) for details. (This is not a legal advice.)

Example video is part of Tears of Steel movie (CC) Blender Foundation | mango.blender.org.

Logo is by @SteveJobzniak.
