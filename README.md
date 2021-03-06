Greg Kikola's Shell Scripts
===========================

These are just a few Bash shell scripts that I occasionally find
useful.

Unless otherwise stated within the file, the contents of each of these
files is licensed under the
[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).
See the file [LICENSE.txt](LICENSE.txt) for full details.


Scripts
-------

* `cargo-checkall`: In a Rust project directory, check for errors, run
  Clippy with `cargo clippy`, and check formatting with
  `cargo fmt -- --check`.
* `cbcopy`: Copy a line of text to the X clipboard (requires `xclip`).
* `cbpaste`: Paste the X clipboard contents to standard out (requires
  `xclip`).
* `checkplaylist`: Read an .m3u playlist and verify that all of the
  files in the playlist exist.
* `listincompatiblefilenames`: Find files within a directory (and its
  subdirectories) having names that might not be compatible with other
  filesystems. If no directory is given, then use the current
  directory.
* `pdfmerge`: Combine separate PDF files into a single PDF file. The
  actual merging is performed using Ghostscript (`gs`).
