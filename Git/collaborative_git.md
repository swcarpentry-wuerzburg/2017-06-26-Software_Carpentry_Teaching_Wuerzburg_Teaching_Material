## Stuff before collaborations.
- Web + git work?
- What can be meaningfully stored in git?
- rm and afterwards checkout.

## Use the web-interface to create a repository ##
(Master permissions are necessary for that in groups)

Showing the web interface:
 - login page https://git.physik.uni-wuerzburg.de
 - Project overview: New project button, issues, todo, profile
 - group overview
 - create a personal project: My thesis
 - Describe the project page(see ALF, it is the most complete that we have)
 - parts: Files browser, commits, cloning address
 - title: Activity, Issue tracking, Wiki
 - create a project in a group

 -> clone the repository
- Create a personal project in the swc group repository 
- pull - change - push cycle
- check back to the web-page to observe the changes.

## Conflicts and resolving conflicts ##
First we need to force a conflict 
- clone the publicrepository
- I will do a change on the local copy of the web-server and commit it.
- Please change the "Hello course" to something personal, like "greetings $YOURNAME" and commit it
- take a step back and consider the histories that have occured. We have 20 different histories by now.
- Should we be able to push?
- Try to push
- changes on the remote end
- pull the changes
- Merge conflict markers
- resolve the conflict by removing the merge markers
- commit the changes.
### Small Game ###
Try to push your changes. If it fails try to pull and adapt to the changes until you can succesfully 
push your changes. 
:-)

- Review the merge graph after the changes and the history in the web interface.

## branches and forks##

Fork the publicexample.
Exercise for home: try to store the names in a python data structure and iterate over that...


### Development models / gitlab flow ###
Exercise with teacher:
in personal project:
- create an issue. describe what you want to do.
- create a branch from that
- do work
- submit the merge request.
- merge it.

### Issue ###
What should you describe in an issue?
- What's wrong?
- What's missing?
- What are you going to do?
- Whose opinions are required?


### Create the feature branch ###

### The Merge Request ###

