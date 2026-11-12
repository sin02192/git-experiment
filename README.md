git switch master
echo "# Project" > README.md
git add README.md
git commit -m "Update README on master"
git switch feature-branch
echo "def login(username, password):" > login.py
echo "    return bool(username and password)" >> login.py
git add login.py
git commit -m "Add login module in feature-branch"
