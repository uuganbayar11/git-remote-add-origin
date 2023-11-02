# git-remote-add-origin
echo "# git-remote-add-origin" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/uuganbayar11/git-remote-add-origin.git
git push -u origin main
