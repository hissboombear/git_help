Creating a New Repository
Go to github.com/hissboombear and login
Click the green "New" button, looks like a book
Give it a name and description
Go to where your code/program is located on your computer
Then run these commands:
```
git init
git add .
git commit -m "First Commit"
git remote add origin https://github.com/hissboombear/Name_Of_Repository
git push --set-upstream origin master
```

Creating a feature branch
Go to github.com/hissboombear and login
Click on the repository you are working on
Click the "Branch: master" button
* Type a descriptive name for the feature you will be adding
* Click "Create branch: descriptive_name_you_typed"
Go back to your GitBash/Command Line Interface
Go to your local Git repository
Then run these commands:
```
git fetch
git checkout descriptive_name_you_typed
