# sqlite3_cj

This file is for sqlite3 v3.37 installation. 

source: https://github.com/sqlite/sqlite

Steps to replace old sqlite:

1. download tar for version of sqlite you want -> https://github.com/sqlite/sqlite/tags
2. untar -> tar -xzf <file.tar.gz>
3. create directory -> mkdir bld (whatever you want)
4. run configure script -> / ../sqlite>configure (sample name)
5. run make -> make (*you may get errors for tl..., install tl..)
6. run make sqlite3.c -> build the amalgamation source file
7. run make test -> test it out
8. run whereis sqlite3 and replace the files with the new files of the new version
