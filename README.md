Pass in an email message with HTML part and this script will open your browser for you to view it. For text mail user agents like mutt.

```
$ viewhtmlmsg --help
usage: viewhtmlmsg [-h] [-s] [-w WAIT] [-b APP] [--fork]

viewhtml - unpack html message and display with browser

optional arguments:
  -h, --help            show this help message and exit
  -s, --safe            view html w/o loading remote files
  -w WAIT, --wait WAIT  remove temporary files after WAIT seconds (0 for keeping files)
  -b APP, --browser APP
                        prefer browser APP over $BROWSER environment
  --fork                fork immediately
```

This is a derived work of the `viewhtmlmsg` script from the [muttils](https://www.blacktrash.org/hg/muttils) project.
