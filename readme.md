# Introduction #

Emacs-helm is an awesome completion and selection interface for Emacs.
and everything (http://www.voidtools.com/) is an ultra fast tool to find files on NTFS file system.
and this  helm-everything is a bridge between Emacs-helm and everything search engine .

warning :
this is just a practice for Emacs-lisp programing. 
I should give special thanks to Martin Weinig <mokkaee@gmail.com> for everything.el.....


to get this  working , you should have "everything" installed, and put "es.exe", command line version of everything, into your PATH.
on the other hand , Helm should be installed within Emacs.


# Install  #
put these following lines into your  .emacs file :

 (add-to-list 'load-path "path/to/helm-everything.el")
 (require 'helm-everything)


#Basic Usage #
just

M-x helm-everything


# TODO #
1. provide es.exe  parameter support 
2. provide more actions after selection
3. avoid lagging, since Emacs is single-thread.
