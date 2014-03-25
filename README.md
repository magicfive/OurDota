OurDota
=======

Use to commit code of new mobile DSP platform

Checkout Code
=======

1. Add your SSH key "rsa_pub" to your profile:

	(1) Click "Account Setting".

	(2) Choose "SSH Keys", then add your private key.

2. Clone the repository:

	git clone git@github.com:magicfive/OurDota.git

Config git
=======

git config --global user.name "your name";

git config --global user.email "your email";

Usage
=======

1. Create local private branch:

	git checkout -b [your private name]

2. Switch branch:

	git checkout [branch-name]

3. See all the branchs:

	git branch

4. Update local branch from remote master branch:

	git pull origin master

5. Check in code:

	git add [filename];

	git commit -m"message";

	git push origin [local branch name]:[remote branch name]

6. Delete branch of remote:

	git push origin :[remote branch name]
 

