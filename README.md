CommitPictures
==============

An easy to way to take a picture after each commit on a Mac and saving the commit message.

# Setup in a specific repository

* Install imagesnap `brew install imagesnap`

* Copy `src/post-commit` located in `.git/hooks/post-commit`

* Modify the script with you favorite folder

* Make sure it is executable `chmod a+x .git/hooks/post-commit`

And it's finish !