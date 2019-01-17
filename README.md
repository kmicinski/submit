# Submitting your work via submit.py

This script, submit.py, is used to download, test, and submit projects
to the autograder. For each new project, you will create a folder with
the project name (e.g., project0) and copy submit.py from this folder
into that folder. That folder can be located anywhere on your disk,
but the project name must precisely match the folder name. For
example, if your username is kmicinski, and you want to work on
a project named `project0` you would do the following:

    # Assuming you have a directory named projects in your home folder
    mkdir ~/projects/project0
    cp submit.py ~/projects/project0

And then you would change into that folder with:

    cd ~/projects/project0

Before using the autograder you need to check the following:

- You have Python 3.7 or later installed.

    $ python3 --version
    Python 3.7.0

- You have the following Python packages installed:
  - requests
  - PyInquirer
  - colorama
  - prettytable

You can install these via `pip3`

    $ pip3 install requests PyInquirer colorama prettytable
