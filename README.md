# SSH Key
- SSH Key is your unique identifier key for your PC
- SSH Key is used to connect with other machines via SSH Connection

# SSH Key Creation
- ssh-keygen -t rsa
- press enter (save to default location)
- copy content of .pub, add it to github: https://github.com/settings/keys

# Git Flow (first time)
git init
echo "# testnow" >> README.md
git add README.md
git commit -m "first commit"
git branch -m main //rename
git remote add origin "origin-url"
git push -u origin main

# Git Flow (subsequently)
git add specific-file
git commit -m "some commit"
git push
