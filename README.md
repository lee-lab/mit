# mit

This is a git-stype content list management tool for Pocket MMDAgent, written in Perl.

# Usage

Execute on the top directory of dialogue content files:

- `mit status` to see current status
- `mit add *files*` to add the specified files to the content list
- `mit add` to add all the files under current to the list
- `mit update` to update file sizes of the files listed in the content list

# simple use

If you simple want to register all files under the directory, do this after an update:
```
% cd content_topdir
% mit add
% mit update
```
