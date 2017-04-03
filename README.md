# ocrad-docker
Docker container image for Ocrad based on Ubuntu. Will install [Ocrad](https://www.gnu.org/software/ocrad/ "ocrad") in the container.
```
For best results the characters should be at least 20 pixels high. If
they are smaller, try the --scale option. Scanning the image at 300 dpi
usually produces a character size good enough for ocrad.
Merged, very bold or very light (broken) characters are normally not
recognized correctly. Try to avoid them.

Usage: ocrad [options] [files]

Options:
  -h, --help                display this help and exit
  -V, --version             output version information and exit
  -a, --append              append text to output file
  -c, --charset=<name>      try '--charset=help' for a list of names
  -e, --filter=<name>       try '--filter=help' for a list of names
  -E, --user-filter=<file>  user-defined filter, see manual for format
  -f, --force               force overwrite of output file
  -F, --format=<fmt>        output format (byte, utf8)
  -i, --invert              invert image levels (white on black)
  -l, --layout              perform layout analysis
  -o, --output=<file>       place the output into <file>
  -q, --quiet               suppress all messages
  -s, --scale=[-]<n>        scale input image by [1/]<n>
  -t, --transform=<name>    try '--transform=help' for a list of names
  -T, --threshold=<n%>      threshold for binarization (0-100%)
  -u, --cut=<l,t,w,h>       cut input image by given rectangle
  -v, --verbose             be verbose
  -x, --export=<file>       export results in ORF format to <file>

If no files are specified, ocrad reads the image from standard input.
If the -o option is not specified, ocrad sends text to standard output.```
