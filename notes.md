'ls' - list

'cd' - change directory

'cd ..' - change to parent directory

'cd ~' - change to home folder

'touch filename.txt' - create a new file

'cp file newfile' - copy a file
'cp -r folder newfile' - copy a folder

'mv oldfile newfile' - move or rename a file or folder

'rm filename' - delete a file
'rm -r folder' - delete a folder
'rm -rf folder' - delete a fodler without confirmation. be careful, there is no undo!

if you ever get an error running a command, EACCESS - error, access.  Try using "sudo" stands for "super user DO"
teh root user can do anyuthing, but this is dangerous

vim is a command-line text editor.

vim has multiple modes: insert mode lets you insert text when you press letetrs
press <Esc> to get into normal mode
type a colon for ex mode:
':wq' - save and quit
':q!' - quit without saving

#GIT
git is a command lien program for tracking changes to a project
github.com is a website that hosts git repositories

'git init' - create an empty git repository; creates the '.git' . folder.
'git status' - ask git about teh current status of the repository ("nothing to commit, working tree clean" means no changes since the last time you've committed)
'git add ." - (stage) prepare all files to be committed
'git commit -m "Message"' - commit staged files
'git log' - shows all git changes recently made (w/ notes)

