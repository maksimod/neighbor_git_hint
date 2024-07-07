# Instruction just for you!
## If you haven`t git bash:
1. Go to [Git](https://git-scm.com/ "GIT!") 
2. Download git bash
## Linux commands:
1. ls - shows files and directions (use flag -a to also watch .git folder)
2. cd "Path to filr" - go to file
3. mkdir "dir name" - create dir
4. touch "file name" - create file
5. rm "file/dir name" - remoce file (-r - remove dir, -rf - force direction remove)
6. mv "path to file1" "path to file2" - move file1 to file2 (-r to move direcrory)
7. nano "file name" - open file in note program (if file doesn`t exist nano will create it)
## Git bash commands:
1. git config  --global user.email "you@example.com"
2. git config  --global user.name "Your Name"
3. git init - initialize git
4. git status - check git status
5. git add . - add all files to git view
6. git commit -m "commit message" commit all files
## Then you need to login/register on github and create your repository
## After that you need to create SSH key:
1. go to home dir 
2. check SSH (they must`t been created, if so, just delete them): ls -la .ssh/ 
3. generate SSH key: $ ssh-keygen -t ed25519 -C "your GitHub account email"
4. press enter 3 times (easier but it`s enough for first time)
5. check file exists: ls -a ~/.ssh (you will see .pub and not-.pub files)
6. copy .pub file text
## then go to github
1. click on your account icon
2. go to settings
3. go to ssh and gpg keys
4. click on new ssh key button
5. in title write ssh key name (my fyrst ssh f.e.)
6. copy from buffer to key form
7. click add ssh key
## go to git bash
1. ssh -T git@github.com 
2. go to your pfoject folder
3. git remote add origin (go to your repository, chose SSH and copy URL and paste instead of "(this comment)") 
4. git remote -v
5. first push git push -u origin main
6. another pushes just git push
# That`s ALL!
