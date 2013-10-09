hps-testrun-nim
===============

# setup user name
$git config --global user.name "perhansson"
$git config --global user.email "phansson@slac.stanford.edu"

# Clone the remote repository
# Recommended:
$git clone https://github.com/perhansson/hps-testrun-nim.git
# For read only:
$git clone git://github.com/perhansson/hps-testrun-nim.git

# fetch latest from remote (local and remote is already configured with clone)
$git pull

# check status of local repository
$git status

# add files to be committed to the local repository
$git add file(s)

# commit files to be committed to the local repository (add -a to commit all staged files)
$git commit -m "Message" file(s)


# push your local changes to the remote (local and remote is configured by clone)
$git push
