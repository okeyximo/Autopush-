 ## Version 1.0 
1. Clone the git repo.

2. Open up the “.bashrc” file (it is in your Home directory, but is hidden by default) in your favorite text editor, like gedit, nano or vi

3. Go to the very end of the file and add:

  `export PATH="/path_of/the_folder_we/want_to_add_to:$PATH"`

5. To register the changes, save the file, exit the text editor and then type in your terminal:
   `source ~/.bashrc`
6. Type `deploy.sh` to run the script in your Terminal and it will prompt you to add a commit message and push to your github.

