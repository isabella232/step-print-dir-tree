# print-dir-tree

Print the structure of an directory to the output log. This step uses [tree](http://mama.indstate.edu/users/ice/tree/) to handle the directory printing.

The tree package will be installed if not availble.

## Options

* `directory` (optional, default: `./`) The directory to print.
* `level` (optional, default: infinite) The maximum level to print, for example: `3` will print only three levels deep.

## Example

    - print-dir-tree:
        directory: $WERCKER_SOURCE_DIR/root
