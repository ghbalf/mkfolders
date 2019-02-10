# mkfolders
Perl script for creating a list of folders

### Usage:
mkfolders {[--destination|-d DESTINATION-FOLDER] [--file|-f FILE] FOLDER1 [FOLDER2 ...]} | {--help|-h|-?}

### where the options are:
    - `--help|-h|-?: show help and exit`
    - `--dest|-d DESTINATION-FOLDER: folder in which the list of folders will be created (default is '.')`
    - `--perms|-p PERMISSIONS: permissions with which the folders should be created (default is 0755)`
    - `--file|-f FILE: file with the list of folder names, one on a line`
    - `FOLDER1, FOLDER2, ...: list of folders to be created`
