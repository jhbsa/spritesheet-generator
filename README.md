# spritesheet-generator
Generates an sprite sheet image, CSS and SCSS from a directory of PNGs, using the power of bash and imagemagick

Usage example: `./generate.sh -ts -n icons`

## Requirements
* Operative System with bash support
* ImageMagick installed and available via bash (for commands like identify, mogrify and montage)
* A folder with PNG files

## Features
* Generates CSS and SCSS sprite sheet styles and a HTML preview file
* Trims empty space individually
* Sorts sprites by size

## Options
* `-h` Show help
* `-t` Trims empty surrounding space of every image before joining them
* `-s` Sorts the images in the sprite sheet by size from smallest to biggest
* `-c <columns>` Maximum number of sprites in every row
* `-n <name>` Relative child folder name, also used as base name for generated files

