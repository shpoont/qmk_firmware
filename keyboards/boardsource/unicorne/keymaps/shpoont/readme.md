# Customized Unicorne Layout
![Customized Unicorne Layout](Unicorne.png?raw=true)

# TODO
- Implement Tap Dance for CMD+C, CMD+X, CMD+V - when pressed returns the character, when held does copy/cut/paste
Inspired by Omer's keymap https://configure.zsa.io/moonlander/layouts/g9NK0/latest/0


# Build

```bash
# Update git submodules
$ make git-submodule
# or
$ git submodule sync
$ git submodule update --init

# Build
$ ./util/docker_build.sh boardsource/unicorne:shpoont
```

# Flash

Use QMK Toolbox to flash the keyboard


# Documentation

https://docs.qmk.fm
