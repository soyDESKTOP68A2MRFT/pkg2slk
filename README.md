# slktools
utilities to convert arch/debian/fedora-RHEL/alpine packages to slackware packages

ps: i uploaded in this repo a script to wrap all other scripts, is called pkgslk, also, in order this scripts to work, you must:

- add the directory in your path
  
- create a directory with the name of the specific script you want to use, this must be done inside the cloned repo folder.
  
- inside each directory must be another directory called "config", in which must be the corresponding .conf of each script, the only script which doesn't need this, is pkgslk (THE WRAPPER, WHICH MUST REMAIN ON PARENT FOLDER).
  
- finally, for comfort, i suggest to put the cloned folder on your path to call all this scripts as if they were normal commands (like cat, or more, or du)
