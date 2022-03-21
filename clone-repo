#!/bin/bash

REPO_LINK="<YOUR REPO LINK>"
JIRA_ID="<JIRA_ID/directory name & branch name to checkout>"

clear 

read -p "Enter jira-id: " JIRA_ID

DIR_NAME="<prefix>-$JIRA_ID"

cd ~/Desktop/<directory to clone>

mkdir $DIR_NAME
cd $DIR_NAME
git clone $REPO_LINK

cd <repo name>
git checkout -b $DIR_NAME

clear

echo $'\nclone and switched to new branched\n'
### below code is used to bump a new verion
# VERSION_BUMP=""

# read -p "version bump? (Y/y/N/n): " VERSION_BUMP

# if [[ $VERSION_BUMP == [yY] || $VERSION_BUMP == [yY][eE][sS] ]]
# then
#     sh bin/tag # command to bump a new version
#     git add .
#     git commit -m "version-bump"
#     git push --set-upstream origin $DIR_NAME
# else
#     echo $'all set!'
# fi
