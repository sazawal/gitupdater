Description:
Bulk update local git repositories.

Platforms:
All linux distributions.
Created and tested on Ubuntu 20.04

Installation:
Run ./install as root
Enter a path directory if asked for. List of path directories can be obtained by running echo $PATH.

Usage:
Place the directories of (downloaded/to-be-updated) git repositories to /opt/gitpackages.
Run gitupdater as root

Function:
All the git repositories placed at /opt/gitpackages are updated one at a time.
The output of gitupdater displays if there is a new update in each of the git repository.

Note:
This package only updates repository code and contents.
Each of the updated repository must be manually installed following their respective documentation.
