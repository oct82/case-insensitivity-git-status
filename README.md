# Case insensitive file system failing git status

This repo is an example on how `git status` can fail on case-insensitive file systems.

To reproduce:

```bash
git clone git@github.com:oct82/case-insensitivity-git-status.git
cd case-insensitivity-git-status
git status ## dirty!!
```
