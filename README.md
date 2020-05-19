# A 2048 C implementation

> This is an implementation of the 2048 game, created with the purpose of learning algorithms in C

> C, SDL2, 2048 game, Graphics Using C

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)


***Insert game screen***

**Insert Game gif**

---

## Table of Contents

- [Installation](#installation)
- [Features](#features)
- [Team](#team)
- [License](#license)


---

## Installation

### Clone

- Clone this repo to your local machine using 

`https://github.com/samuelgamito/2048-C.git`

### Setup

- Install SDL2 on Linux

> If you have some Advanced Packaging Tool available (ie Ubuntu and Debian) use the follow commands

```shell
#install sdl2
$ sudo apt install libsdl2-dev libsdl2-2.0-0 -y;

#install sdl image
$ sudo apt install libjpeg9-dev libwebp-dev libtiff5-dev libsdl2-image-dev libsdl2-image-2.0-0 -y;

#install sdl mixer
$ sudo apt install libmikmod-dev libfishsound1-dev libsmpeg-dev liboggz2-dev libflac-dev libfluidsynth-dev libsdl2-mixer-dev libsdl2-mixer-2.0-0 -y;

#install sdl true type fonts
$ sudo apt install libfreetype6-dev libsdl2-ttf-dev libsdl2-ttf-2.0-0 -y;
```

> If somehow you don't have a package manager, you can install from the source the classic Unix way.

> Download the source code from [SDL Website](https://www.libsdl.org/download-2.0.php#source)

```shell
# Using Curl
$ curl https://www.libsdl.org/release/SDL2-2.0.12.tar.gz --output SDL.tar.gz
```
> Now extract the SDL, configure and make to install 
```shell
$ mkdir sdl
$ tar -zxf SDL.tar.gz -C ./sdl
$ rm SDL.tar.gz
$ cd sdl
$ ./configure
$ make all
$ make install
```

- Install SDL2 on Windows

<a href="https://www.libsdl.org/download-2.0.php#source" target="_blank">Follow the SDL steps on.</a>

---

## Features
<ul>
<li><input checked="" disabled="" type="checkbox"> Homepage with options(Play, Scores, Load Game)</li>
<li><input checked="" disabled="" type="checkbox"> Save game options </li>
<li><input checked="" disabled="" type="checkbox"> List of Last scores saved </li>
<li><input checked="" disabled="" type="checkbox"> Use keyboard arroy to play</li>
<ul>
Supported Languages:
<li><input checked="" disabled="" type="checkbox"> Portuguese </li>
<li><input disabled="" type="checkbox"> English</li>
</ul>
</ul>

## Usage
> The first implementation was using Code Blocks and Windows, and was a first contact with C and SDL. The Linux implementation is something like a remastering,  then the project it's more organized and easy to run or build
### Using on Windows

The project was created using [Code Block](http://www.codeblocks.org/), so the best way is open the windows project as Code Blocks project and run or build using this him.

### Using on Linux

An Linux version is comming soon

---

## Team

> 
| <a href="https://github.com/samuelgamito" target="_blank">**Samuel Gamito**</a> |
| :---: |
| [<img src="https://avatars2.githubusercontent.com/u/12644639?s=460&u=4a0475c4309b27a91bb87f3adb13745ea76a917e" width="250">](https://github.com/samuelgamito)  |
| <a href="https://github.com/samuelgamito" target="_blank">`github.com/samuelgamito`</a> |

---

## License

[![License: GPL v3](https://img.shields.io/badge/License-GPL%20v3-blue.svg)](http://www.gnu.org/licenses/gpl-3.0)

- **[GNU General Public License](http://www.gnu.org/licenses/gpl-3.0)**
