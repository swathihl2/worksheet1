# worksheet1

## Prerequisite:
a. Created github.com account: www.github.com

b. Downloaded git: https://git-scm.com/download/win

## Assign the work
1. Open https://docs.google.com/spreadsheets/d/1eEjsJvywPsJL2EUJ3wwU8Os8fYDL-4bN7LgEPQZVh-M/edit?usp=sharing
2. In the "Assigned to" Column, Add your name. (Choose a word which others have not put their name already in)

## Execute steps
1. Clone the repository to your local machine
```
git clone https://github.com/pallavrustogi/worksheet1.git
```
2. Enter the directory worksheet1
```
cd worksheet1
```
3. create a new branch from the "main" branch. This new branch should contain your name.
```
git checkout -b "your_name_branch" main
```
4. Open the file spell.txt in a notepad
```
notepad.exe spell.txt
```
5. Find the word assigned to you from step 1, and change '^' to 'a', '3' to 'e', '1' to 'i', '0' to 'o', ')' to 'u' and save the file
6. Check if your changes are correct by following steps
* Check if spell.txt is modified
```
git status
```
* Check you changed only what you wanted to change
```
git diff spell.txt
```
7. If everything looks good from step 6, add the file to staging area
```
git add spell.txt
```
8. Check the git status again
```
git status
```
9. Commit the file with comments
```
git commit -m "Corrected the spelling"
```
10. push the changes to remote repository on github.com
```
git push
```
or
```
git push --set-upstream origin your_name_branch
```
11. Create a pull request, Visit https://github.com/pallavrustogi/worksheet1 and click on compare & pull request. Then click on create pull request.

## Next steps
If you have completed above steps, you have learnt basics of github. Explore and learn further:
* https://guides.github.com/activities/hello-world/
* https://product.hubspot.com/blog/git-and-github-tutorial-for-beginners
* https://www.freecodecamp.org/news/the-beginners-guide-to-git-github/
* https://www.atlassian.com/git/tutorials/advanced-overview


