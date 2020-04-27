# Git Tutorial: A Comprehensive Guide

solid understanding of the [__Command Line__ ](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) is required befor beginning this tutorial **Recommended**.

## Version Control
Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.

There is three Version Controls we need to understand : **LVCS,VCS,DVCS***


### Local Version Control :
programmers created Local Version Control systems. 
A LVCS entails one database on your hard disk that stores changes to files.



### Centralized Version Control (CVCS):


![CVCS](https://www.edureka.co/blog/wp-content/uploads/2016/11/Centralized-Version-Control-System-Workflow-What-Is-Git-Edureka.png)

This system entails a **single server** storing all changes and file versions, which **can be accessed by various clients**.
which eliminates the need to involve all ~~local databases~~ and allowe programmers to have more knowledge of team members’ activitie

The need for collaboration within a developer team on 
a single file or set of files led to the advent of 
the Centralized Version Control System (CVCS). This system entails 
a *single server* storing all changes and file versions,
which can be accessed by various clients


### Distributed Version Control (DVCS):
A Distributed Version Control systems (DVCS) addresses the major vulnerability of the CVCS failure:

DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

# What is Git?


![GIT-IMAGE](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2016/11/Git-In-Devops-What-Is-Git-Edureka-2.png "Git life sycle")



Git is a combilation of files ( __Snapshots__) that programmers save ( __Commit__) to be stored as new version with its time and programmer's info. 
If the file has not changed, Git only stores a reference to the already-stored identical version of it.


## Three States of Git's File
+ Committed
    -  Data is securely stored in a local database
+ Modefied
    - File has been changed but not committed to the database
+ staged
    - Flagged a file’s changed version to be committed in the next snapshot

## Setting up a Git Repository
 After  you create a Repo on your GitHub follow the commands with ubuntu
 
``` Git
$ git clone https://github.com/YOUR REPO

```

### Check File Status
To determine the state of files, utilize the git status command:
``` Git
$ git status

```

### Tracking and Staging a New File
To Add a  *Single File*
``` Git
git add filename

```

To Add *All Files*
``` Git
$ git add *

```


#### *After using these commands, files are tracked and staged for committing.



### Committing a File
After staging one or multiple files, you should commit the changes and record what you did within the commit message:
``` Git
$ git commit -m “made change x,y,z”

```

### Committing All Changes
``` Git
$ git commit -a

```
### Pushing Changes

``` Git
$ git push origin master

```




