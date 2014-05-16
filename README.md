

AsiaCoin is a 100% pure POS currency

AsiaCoin v2.1.0.0 (non breaking update)

AsiaCoin - BC fork development tree

This is the Official fix for Asiacoin, changes include:

    Blocks address of premine wallet holding 3.2B so it cannot be used to either trade or stake (this is the key change!)
    Allow for 1% staking even after 10 years.. ad infinitum
    New POS schedule: 100% -> 1% over 4 years, gradual decline
    Reverted many of the original bad code used to hide the premine, made premine explicit in code
    Integrated new logo and icons
    Edited about dialog box to reference thread, new website and new github repo
    edited makefile and qt.pro file to build on windows
    fixed some windows build failures
    added some new seed servers and dns seed that i control
    added checkpoint
    Increased version to v2.1


Development process
===========================

Developers work in their own trees, then submit pull requests when
they think their feature or bug fix is ready.

The patch will be accepted if there is broad consensus that it is a
good thing.  Developers should expect to rework and resubmit patches
if they don't match the project's coding conventions (see coding.txt)
or are controversial.

The master branch is regularly built and tested, but is not guaranteed
to be completely stable. Tags are regularly created to indicate new
stable release versions of AsiaCoin.

Feature branches are created when there are major new features being
worked on by several people.

From time to time a pull request will become outdated. If this occurs, and
the pull is no longer automatically mergeable; a comment on the pull will
be used to issue a warning of closure. The pull will be closed 15 days
after the warning if action is not taken by the author. Pull requests closed
in this manner will have their corresponding issue labeled 'stagnant'.

Issues with no commits will be given a similar warning, and closed after
15 days from their last activity. Issues closed in this manner will be 
labeled 'stale'.
