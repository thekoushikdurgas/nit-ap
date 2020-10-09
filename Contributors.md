Change to the repository directory on your computer (if you are not already there):



```

cd first-contributions

```

Now create a branch using the `git checkout` command:

```

git checkout -b <add-your-new-branch-name>

```



For example:

```

git checkout -b add-alonzo-church

```

(The name of the branch does not need to have the word *add* in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)



## Make necessary changes and commit those changes



Now open `Contributors.md` file in a text editor, add your name to it. Don't add it at the beginning or end of the file. Put it anywhere in between. Now, save the file.



<img align="right" width="450" src="assets/git-status.png" alt="git status" />





If you go to the project directory and execute the command `git status`, you'll see there are changes.





Add those changes to the branch you just created using the `git add` command:



```

git add Contributors.md

```



Now commit those changes using the `git commit` command:

```

git commit -m "Add <your-name> to Contributors list"

```

replacing `<your-name>` with your name.



## Push changes to GitHub



Push your changes using the command `git push`:

```

git push origin <add-your-branch-name>

```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.



## Submit your changes for review



If you go to your repository on GitHub, you'll see a  `Compare & pull request` button. Click on that button.



<img style="float: right;" src="assets/compare-and-pull.png" alt="create a pull request" />



Now submit the pull request.



<img style="float: right;" src="assets/submit-pull-request.png" alt="submit pull request" />



Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.



