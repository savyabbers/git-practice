# Starting a new Project

When you are starting a new git project you can start from scratch. Or make a existing dir a new git and start tracking.

## Init

    $ git init

`git` will make a new git repository and wait for you to add files to start tracking.

## Stage

To start tracking items you must first stage them and commit to them. To add files to a stage you would type the command then a file name.

    $ git stage file-name

----

You can stage multiple files using the shell's `*` (star) function.

But its better for you to let git use its own `*` this way its expaned to much more than the one directory. it will grab all sub-directories too.

    $ git stage src/\*.c
    $ git stage src/\*.h

This will grab all the files and sub-directories on the src directory that are `.c` and `.h` files.

    $ git stage src/*.c
    $ git stage src/*.h

This example will only grab files that are in the src directory and no sub-directories
