## Research Questions 


1. What is Git? 
Git is an Open Source Distributed Version Control System which is used for tracking changes in any set of files, usually used for coordinating work among programmers during software development.  
2. What is the difference between Git and GitHub? 
Git is the actual software version control system that lets you manage and keep track of your source code history as opposed to to GitHub which is a cloud-based hosting service that lets you manage Git repositories. 
3. Why do we create a branch? 
Git branches are created to isolate specific Git commits from the rest of your main Git history. 
4. What is the purpose of a Pull Request? 
Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main. 
In order to switch between branches one must use the "git switch" command and specify the name of the branch one wants to switch to. In this case, you would use command "git switch" along with the name of the main branch. 
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 
The 'git pull' command first runs git fetch which downloads content from the specified remote repository. Then a 'git merge' is executed to merge the remote content refs and heads into a new local merge commit. So, the 'git fetch' is about retrieving data from a remote repository whereas, 'git merge' is about combining work from multiple lines of work. 
7. What is a merge conflict? 
Merge conflicts happen when you merge branches that have competing commits, and Git needs your help to decide which changes to incorporate in the final merge. 
8. How do you resolve a merge conflict? 
You go to the repository and click pull requests. Then, in the pull request list click pull request with a merge conflict you would like to resolve. Last, near bottom of pull request, click resolve conflicts. 