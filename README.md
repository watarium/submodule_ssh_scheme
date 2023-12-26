# submodule_ssh_scheme

submodule test with ssh. Modified submodule command as below.

original: git submodule add https://github.com/watarium/cocoon_drop.git cocoon

modified: git submodule add ssh://github.com/watarium/cocoon_drop.git cocoon


git init

git add README.md

git commit -m "first commit"

git branch -M main

git submodule add ssh://github.com/watarium/cocoon_drop.git cocoon

git push -u origin main

