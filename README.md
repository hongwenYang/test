…or create a new repository on the command line
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/hongwenYang/test.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/hongwenYang/test.git
git branch -M master
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
