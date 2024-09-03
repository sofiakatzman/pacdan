# Pacdan

This is a clone of the original pacman by Namco, reskinned to be themed for a birthday gift.
Theme: Uruguay Nacional Soccer Team

## Install hint

You have to compile the Linux version on your own. For this, you'll need

- libsdl2
- sdl2-image
- sdl2-ttf
- and sdl2-mixer.

```
sudo apt install libsdl2-2.0-0 libsdl2-dev libsdl2-image-2.0-0 libsdl2-image-dev libsdl2-ttf-2.0-0 libsdl2-ttf-dev libsdl2-mixer-2.0-0 libsdl2-mixer-dev

```

Then, download and extract the zip file or clone the pacman repository.
Inside the pacman directory, run

```
./autogen.sh
./configure
make
make install
```

## License

Pacman is licensed under the terms of the GNU General Public License version 2 (or any later version).
