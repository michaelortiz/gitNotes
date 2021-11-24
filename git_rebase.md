# git rebase

## git rebase --interactive

git rebase --interactive HEAD~2

## git rebase --> using merge --squash
git checkout <your-branch>

git reset --hard origin/develop # resets you to develop

git merge --squash origin/<your-branch> # merges all the contents of your branch as a single commit

git commit # give it a good commit message

git push origin --delete <your-branch> # delete branch from server

git push -u origin <your-branch> # push it back to server And now, reopen the PR
