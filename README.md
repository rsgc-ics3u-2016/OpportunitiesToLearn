# Opportunities To Learn

This repository is intended for use by the Grade 11 Introduction to Computer Science class at Royal St. George's College in 2016-17.

If you are a student in this class, you are the audience for this README file.

This repository is the source of tutorials and activities that we will use in the course going forward.

(If you are not a student in this class, you are welcome to browse around, as well.)

## How to use

As a student, you do not have write access to this, the master repository.

You will [create a *fork* of this repository](https://github.com/rsgc-ics3u-2016/OpportunitiesToLearn/blob/master/README.md#to-create-a-fork-of-this-repository).

Then, you will [clone the forked repository to your computer](https://github.com/rsgc-ics3u-2016/OpportunitiesToLearn#to-clone-this-repository-and-create-a-local-working-copy), to create a *local working copy*.

On your computer, a *remote origin* (a pointer to your forked repository on GitHub.com) will automatically be created for you.

At regular intervals, you will *commit changes* to your local working copy of your repository (like pressing "Save" when editing an essay).

At regular intervals, you will *push the changes* from your local working copy to your forked repository's remote origin on GitHub.com. This is like "handing in" your work, and **will replace making snaps on Sesame** going forward.

Finally, on occasion, you will need to *pull and merge changes* from the master repository to obtain new activities and opportunities to learn from me, your teacher.  As a one-time setup item, you need to [make a pointer to the remote copy of the master repository](https://github.com/rsgc-ics3u-2016/OpportunitiesToLearn/blob/master/README.md#how-to-make-a-pointer-to-the-remote-master-repository).

Instructions on how to perform all of these operations are described below.

### To create a fork of this repository

* Keep these instructions open in one window. Open a second browser window. [Navigate to the main page of the repository](https://github.com/rsgc-ics3u-2016/OpportunitiesToLearn).
* Locate the *fork* button in the top right corner of the page, and click it.
![Fork](http://russellgordon.ca/rsgc/2016-17/ics3u/fork.png)
* Choose your own account as the destination of where to store your fork. NOTE: Your account picture may not be quite as handsome!

![Select account to fork to](http://russellgordon.ca/rsgc/2016-17/ics3u/account.png)

* After a few seconds, you will see your own fork of the repository. Look carefully at the repository name – this is how you know that you are in *your fork* and not the master repository.

![Your fork](http://russellgordon.ca/rsgc/2016-17/ics3u/yourfork.png)

### To clone this repository and create a local working copy

* Locate and press the green **"clone or download"** button:

![Clone or download](http://russellgordon.ca/rsgc/2016-17/ics3u/clone-button.png)

* Select and copy the repository address to your clipboard (Command-A then Command-C):

![Get repo link](http://russellgordon.ca/rsgc/2016-17/ics3u/repo-link.png)

* Open Xcode.

* Select this menu sequence: Source Control > Check Out:

![Check out menu item](http://russellgordon.ca/rsgc/2016-17/ics3u/checkout.png)

* At the bottom of the dialog that appears, paste the address stored in your clipboard, and press Next.

![Pasting repository address](http://russellgordon.ca/rsgc/2016-17/ics3u/repo-address.png)

* At the next page, you will likely be asked to log in with your GitHub.com username and password. Do so.

* Then you will be asked to choose **where to save** the local copy of the repository. This can be anywhere **except within a folder synced to Google Drive**.  Please **do not** save the repository inside a folder synced to Google Drive, as this will corrupt the repository's data!

* You will see Xcode download and create the local working copy of your fork of this repository.

### How to make a pointer to the remote master repository

NOTE: This is a one-time setup step.

* Open a Terminal window.

![Opening a Terminal window](http://russellgordon.ca/rsgc/2016-17/ics3u/terminal.png)

* In Finder, locate the folder that contains your fork of the *OpportunitiesToLearn* repository.

![Finding your repository](http://russellgordon.ca/rsgc/2016-17/ics3u/find-repo.png)

* In the Terminal window, type **cd** then drag and drop your repository folder to the Terminal window, then press the *Enter* key:

![Drag and drop](http://russellgordon.ca/rsgc/2016-17/ics3u/drag-and-drop.png)

![Switch to repo folder](http://russellgordon.ca/rsgc/2016-17/ics3u/switch-to-repo.png)

* List the current configured remote repository for your fork by typing **git remote -v**:

![List remotes](http://russellgordon.ca/rsgc/2016-17/ics3u/list-repos.png)

* Specify the new remote upstream repository that will be synced with the fork, with the command **git remote add teacher-upstream https://github.com/rsgc-ics3u-2016/OpportunitiesToLearn.git**

![Set upstream repo](http://russellgordon.ca/rsgc/2016-17/ics3u/set-upstream.png)

* Check that the new remote was added with command **git remote -v** again:

![Verify new upstream](http://russellgordon.ca/rsgc/2016-17/ics3u/verify-new-upstream.png)

### How to update from the class master repository

* From the Source Control menu item, choose Pull:

![Pull](http://russellgordon.ca/rsgc/2016-17/ics3u/pull.png)

* In the **Pull remote changes** sheet that appears, choose the new remote you set up:

![New repo](http://russellgordon.ca/rsgc/2016-17/ics3u/new-repo.png)

(to be continued)

