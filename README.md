## for deleting branch

///////// -- local -- ////////////

 git branch -d dev

  git branch -d test

 ///////-- remote --/////////////

git push origin :dev

git push origin :test

## annotated tags  vs  lightweight tags

1) Annotated Tag: 
1-Contains a message, date, and author info.
2-Can be GPG-signed.
3-Used for official releases.

2) Lightweight Tag:
1-Just a pointer to a commit, no extra info
2-Used for temporary or quick marking


## Use git rebase when:
1- You want a cleaner, linear history 
2- update your branch 
2- want to edit commits before pushing

## list tags

git tag

## delete tag

///////////// --locally -- //////////
git tag -d tag_name

///////////// --remotely -- //////////

git push origin --delete tag tag_name


[Click here](https://th.bing.com/th/id/R.9a0ee667cd80d21ba3a7c75f99b66563?rik=PbSUuB%2b3YtM%2frA&riu=http%3a%2f%2fwallpapercave.com%2fwp%2fFhndtDK.jpg&ehk=QfeFP61tcgMIHlOkafRNcGDLqRtDE5r7NzUavYlkCOU%3d&risl=&pid=ImgRaw&r=0)