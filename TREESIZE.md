# Treesize

* [pyfileutils](README.md)
* [Code](treesize)

This scripts walks a directory tree and outputs the total file count and total file size in bytes. This is useful because the macOS's version of `du` does not support `--apparent-size` unlike GNU's.

## Usage

```
usage: treesize [-h] [--recursive | --no-recursive] STARTDIR

Report total file count and file bytes for directory tree

positional arguments:
  STARTDIR

optional arguments:
  -h, --help      show this help message and exit
  --recursive     recurse into directory
  --no-recursive  do not recurse into directory
  --progress      show files as they are processed
  --no-progress   do not show files as they are processed

https://github.com/rcook/pyfileutils
```

## Example

```
./treesize .
```

## Licence

Released under [MIT License][licence]

Copyright &copy; 2018, Richard Cook. All rights reserved.

[exifread]: https://pypi.org/project/ExifRead/
[find-duplicates]: https://gist.github.com/jinie/b51f75fa1ece7c02ca3f/
[licence]: LICENSE