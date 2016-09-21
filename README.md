# Overview

Similar to linux `find` it walks the given directory and returns a list of files and directories.

# Basic Usage

```
finder
```

By default this returns a list of files and directories ignoring hidden files/directories and paths matching any matchers found in .gitignore and .agignore files

# Advanced Usage

```
finder --all                    # no files will be ignored
finder --directories-only       # only returns the directories found
finder --files-only             # only returns the files found
finder ${HOME}                  # walk your home directory
```


## TODO Overall

- Speed up using threads
