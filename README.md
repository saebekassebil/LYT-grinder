# Grinder

A tool for concatenation and dependency management of CoffeeScripts.
Refactored from the [LYT](https://github.com/Notalib/LYT/) source code

## Installation

    $ npm install lyt-grinder

## API

### `exports.grind = function(loadpaths, files)`
Takes two strings (or arrays of strings) - loadpath(s) and the file(s) to be resolved.
The function returns the concatenation order of all the resolved files