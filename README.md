# WINPEN

A pendrive to carry a POSIX shell (busybox) and a prefix
for Microsoft Windows system administration.

## Features.

- A POSIX Shell : busybox.
- ANSI escape support : ansicon.
- Automatic Pendrive formatting.
- Automatic installation on pendrives.
- Automatic upload by OpenSSH.
- DAV Software fetching and uploading to store installers.
- [sh-hutil](https://github.com/harkaitz/sh-hutil) Shell utilities.
- [sh-hformat](https://github.com/harkaitz/sh-hformat) Drive formatter.
- [sh-hdav](https://github.com/harkaitz/sh-hdav) DAV client.
- 7z extractor.

## Help

winpen

    Usage: winpen ...
    
    Manage a directory in `~/.winpen` to store software for MS Windows.
    
    ... collect          : Download "busybox" and "ansicon".
    ... prepare          : Run the initial setup of `~/.winpen`.
    ... format DRIVE     : Format drive with FAT.
    ... rsync  DRIVE     : Update drive with changes in `~/.winpen`.
    ... upload SSH       : Upload `~/.winpen` in a windows machine.
    
    ... sh[32]           : Open shell with wine (32/64 bits).
    
    ... ins-u URL [NAME] : Download installer and save in repo.
    ... ins-d FILE       : Download installer installer's dir.

## Collaborating

For making bug reports, feature requests and donations visit
one of the following links:

1. [gemini://harkadev.com/oss/](gemini://harkadev.com/oss/)
2. [https://harkadev.com/oss/](https://harkadev.com/oss/)

