# This repository contains a Bash script that reads through users and groups in a file and creates these users and groups as specified.

Additionally, the script does the following:

- Creates home directories for each user
- Generates random passwords for each user
- Logs all actions to `var/log/user_management.log`
- Stores all the users and their generated passwords in `/var/secure/user_passwords.txt file`
- To run this Bash script, ensure that your terminal is currently opened as the root user.

Next change your current directory to the directory holding the `create_user.sh` file and the `text_file.txt.`

Then run this command:
```
./create_user.sh ./text_file.sh
```