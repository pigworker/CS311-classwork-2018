CS311 Classwork Repository
==========================

This repo will grow to contain the proforma for each of the CS311 group classwork exercises.

It will also contain any software that is necessary to undertake CS311 classwork, e.g., the CS311 compiler-interpreter and the massive machine emulator.


Getting Started
---------------

Your group (named after a chemical element) needs a version of this repository with your collective solutions.

1. *Everybody*, using a lab machine booted up to linux, open a web browser and visit [departmental GitLab](https://gitlab.cis.strath.ac.uk/). Make sure you can log in, asking for a password reset if you need one.

2. *Everybody*, make sure you can connect with GitLab using ssh. You may need to create an ssh key, using ssh-keygen. If the command `ls ~/.ssh` draws a blank, run `ssh-keygen` and try again. Once you have a file called `~/.ssh/id_rsa.pub`, navigate on your browser to your gitlab settings page (via menu top-right), then to the SSH keys page (icon of a key in the left sidebar) and paste in the contents of `~/.ssh/id_rsa.pub` to establish your credentials.

3. *One person per group*, make a local copy of this repository by the command `https://github.com/pigworker/CS311-classwork-2018.git`.

4. *Same person per group*, create a new project on GitLab with the name CS311-2018-<chemical-element> (i.e., your group's name). Do not initialise it with any content via the website.
Instead, copy the project's url (the ssh one) to the clipboard and, from a terminal window with current directory inside your local copy of this repository, issue the command `git remote add group <pasted-url>`. And then `git push -u group master`. That should initialise your group repo from this one.

4. *Same person per group*, on GitLab, invite the rest of your group to the project. (The settings menu from the left sidebar gives you a "members" option.) Make sure you add your colleagues as Maintainers. Please also invite "Conor McBride", "Neil Ghani", "Stuart Gale" and "Benjamin Price" as maintainers. We're in your team, too!

5. *Everybody*, accept invitations from GitLab, then make your own local copy of the group repository. GitLab will offer you an ssh url for the project: copy it to the clipboard then issue the command `git clone <pasted-url>` and that should create your copy of your group's repo.

6. *Everybody*, get cracking!


