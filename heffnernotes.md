
# March 31, 2020
Working with GitHub and Virtual Studio
1. Hello everyone.  The Boomer is learning how to use github.
2. Process for making a repository in GitHub
3. Create a naming convention and create a new repository
4. Create a new file
5. Copy to URL to GitHub Desktop
6. Clone repository in Github
7. Open in Virtual Studio
8.  Commit the repository
# April 7, 2020 
Class Notes
Linux Remote access on AWS
The server looks for a public key.  
Its more difficult to brute force a key
1. convert the PEM key with putty gen
2. save as a privat key
3. put key in authentication area of putty
4. paste ip and open
5. sudo = super user do
6. sudo adduser "user name" --disabled-password = so the instance will only use a key
7. sudo su - "user name"
8. mkdir .ssh = create a ssh in home directory hides the directory
9. ls -la displays hidden files
10. chmod 700 .ssh = write permissions = changes file permission for the user to have read, write, execute
11. touch .ssh/authorized_keys
12. chmod 600 .ssh/authorized_keys = changes file permission for the user to have read, write
13. ssh-keygen = generates a key pair
14. cd .ssh
15. ls
16. cat authorized_keys = to view key
17. 





