# Git Collaboration

This repository provides an exercise for practicing Git/Github collaboration
skills.  To complete this exercise, you will need to work with a partner to
complete it.  If you have not sure how to find a partner, please reach out to course staff for assistance.

For this exercise, one of you will be the "owner" of the repository, and the
other will be the "contributor".

To fully complete this exercise, you will need to do the entire exercise
twice, with each of you taking turns being the "owner" and the "contributor".

You may notice that this repository contains no files other than this README.
This is intentional, as the focus of this exercise is on collaboration using
Git and GitHub, rather than working with existing code.

## Owner Forking the Repository and Adding Collaborator

1. The owner should start by forking this repository to their own GitHub
   account. You should be familiar at this point with how to do this.  When
   forking, be sure to change the name of the repository to include your GitHub
   username to make it unique (e.g., "software-dev-course-git-collab-mlambert").
2. Once the repository is forked, the owner should clone their fork to their
   local machine.
3. The owner should then add the contributor as a collaborator to their forked
   repository on GitHub. To do this, you will need to get the GitHub username
   of your partner.  

## Contributor Cloning the Forked Repository

1. The contributor should clone the owner's forked repository to their local
   machine. The URL for cloning can be found on the main page of the owner's
   forked repository on GitHub.
2. The contributor should then create a new branch named `contributor-branch`
   in their local clone. This can be done through Visual Studio Code, or by
   using the appropriate terminal command.
3. The contributor should add a new file to the repository named
   `contributor.txt`. In this file, the contributor should add a single line of
   text that says: `This file was added by [contributor's GitHub username].`
4. The contributor should then commit their change and push the
   `contributor-branch` to the owner's forked repository on GitHub.
5. Once the branch is pushed, the contributor should create a pull request from
   the `contributor-branch` to the `main` branch of the owner's forked
   repository on GitHub.
6. The contributor should notify the owner that the pull request has been
   created.

## Owner Merging the Pull Request

1. The owner should open GitHub, click on their inbox and review the pull
   request created by the contributor. (This means looking at the changes
   proposed in the pull request on GitHub.)
2. If everything looks good, the owner should merge the pull request into the
   `main` branch of their forked repository using the GitHub web interface.
3. After merging the pull request, the owner should open the repository in
   Visual Studio Code or a terminal and run a `git pull` to update their local
   `main` branch with the changes from the merged pull request.

## Improving Your Understanding

To further improve your understanding of Git collaboration, try having both
partners make additional changes to the repository on new feature branches and
create pull requests for each other to review and merge.  This will give you
more practice with the Git collaboration workflow.

Consider and discuss how you might use this process to work with your team
member on a larger joint porfolio project.

## Conclusion

By completing this exercise, both partners should have a better understanding
of how to collaborate using Git and GitHub. Feel free to reach out to the instructor
if you have any questions or need assistance during the exercise.

