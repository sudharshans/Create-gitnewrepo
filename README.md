
# Steps to create a new git repository using command line:
vim README.md <br />
git init <br />
git add README.md <br />
git commit -a -m "First Commit" <br />
git remote add origin "https://github.com/sudharshans/Create-gitnewrepo" <br />
git push -u origin master (in case of error: git push -f origin master) <br />

# Push an existing repository from the command line:
git remote add origin "https://github.com/sudharshans/Create-gitnewrepo" <br />
git push -u(or -f) origin master <br />
