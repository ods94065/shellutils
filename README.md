# Shell Utilities

These are various command-line scripts I've written for shell use.

## backinup

      backinup [OPTIONS] FROM-DIR TO-DIR PATHS...
      backinup [OPTIONS] FROM-DIR TO-DIR -
    
    Backs up files from one top-level directory to another.
    Paths may be specified on the command line, or if - is specified,
    they may be provided to standard input, one per line.
    
    All paths given must be relative to FROM-DIR.
    
    Options:
        -v, --verbose                    Run verbosely
        -h, --help                       Print help
