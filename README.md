# filesort-rs
A conversion of my filesort project written in Rust.


# Release versions

Note that `main` is generally a work in progress, and you probably want to use a tagged release version.

# Quick start
To use filesort you pass in the name of the file you want sorted along with several optional parameters.

* --input-file,       Source file to sort
* --output-file,      Destination file to write to
* --descending,       Sort file in descending order
* --version,          Filesort version
* --help,             Filesort help
* --line,             Reads data in per line
* --word,             Reads data in per word rather than per line

## Example
* `filesort --input-file test.txt --output-file output.txt` Reads the data from test.txt and writes it to output,txt in ascending

# Requirements
You must have the Rust compiler installed.

## Getting
`git clone --recursive https://github.com/jlechem/filesort`

### Building
* Navigate to the filesort-rs directory and use cargo build --release

