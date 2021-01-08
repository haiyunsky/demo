# demo

mkdir demo

cd demo

echo "# demo1" >> README.md

git init

git add README.md

git status

git commit -m "first commit"

git remote add origin git@github.com:mskill/demo1.git

git push -u origin master

-------------------
git pull

-------------------------
git branch mybranch

git checkout mybranch

echo "# test branch1" >> test_branch.txt

git push --set-upstream origin mybranch

git push

---------

git checkout master

git merge mybranch










