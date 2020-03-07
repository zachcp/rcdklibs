## Comments to CRAN Staff

1. This package is submitted with the rCDK 3.5 package. 
2. This package is a 25MB upload, far exceeding the standard upload size. We have discussed this in the past and were given a waiver on previous submissions. It has been discussed in the past that these may be a better on-CRAN way to pull in Java JAR files, but so far as I am aware, these is nothing that is CRAN compatible. If you are aware of changes that would allow us to sideload the cdklibs jars, I can adopt our package to such a workflow. In the meantime, I would request a continuation of uploads.


## Local Test environments
* local OS X install, R 3.6.3
* Ubuntu Linux 16.04 LTS, R-release, GCC
* win-builder (release and devel)

## R CMD check results

For devtools::check_win_release()

0 errors | 0 warnings | 1 note
The note is related to the Orphan status.


