This is the SecondFloor Allianz Remote testing repository
=========================================================

Reference Portfolio
===================

Git intro
---------

To setup you GIT Client please do the following commands:
Setup your environment

Configure your username and email:
$ git config --global user.name "Your Name"
$ git config --global user.email your.email@<server>


Use rebase instead of merge when pulling:
$ git config --global branch.autosetuprebase always


Push only the current tracking branch instead of every branch:
$ git config --global push.default upstream


Use colors on the command line:
$ git config --global color.ui true


For any questions regarding this repository please contact your Project Manager

Branching
---------

Currently three branches are setup with the following purposes:

1. master
Contains the last full snapshot zip that was delivered by Allianz RAI Test team.
Could be updated with new files identified by RAI test team, according to the 'old' file structure.

2. 8.6
Contains AMOS work in progress to re-align the reference portfolio file structure to the 'new' structure.
Will be merged back to master once the qtp scripts and input data is all re-aligned. And qtp runs successfully against the new structure.

3. 8.7
Contains SF work in progress to:
* re-align the reference portfolio with 8.7 CRs
* re-align any structural changes agreed between SF and Allianz on the folder structure

Tagging
-------

Currently we have no concrete guidelines in place with regards to tagging, but we agree that tags are used whenever a 'natural' version
or point in time milestone is reached on the full repository.
