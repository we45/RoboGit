## RoboGit

Robot Framework Library for Basic Git Operations

**Currently supports only unauth clone. Mostly meant as a way of supporting
git operations in a pipeline**

### Requires
* Python 2.7.x
* GitPython
* Robot Framework

### Install

`pip install RoboGit`

### Run

#### Keywords

**clone repository from url**

Clones the repo (url) to a directory on the local machine

`| clone repository from url  | repo_url  | to_path  | branch (optional)`

**clear contents from directory**

clears contents from target directory

`| clear contents from directory  | path (target)  |`

