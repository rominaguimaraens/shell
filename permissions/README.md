0-iam_betty --> changes current user to betty
1-who_am_i --> prints name of current user
2-groups --> prints all groups user is a part of
3-new_owner --> changes the owner of hello to user berry
4-empty --> creates an empty file called hello
5-execute --> adds execute permission to owner of the file hello
6-multiple_permissions --> adds execute permission to owner and group, read permission to other users
7-everybody --Z adds execute permision for all
8-James-Bond --> sets permision for the file hello: owner no permission, group no permission, other users all permissions
9-John_doe --> sets permissions of hello to -rwxr-x-wx
10-mirror_permissions --> sets hello permissions to be the same as olleh permissions
11-directories_permissions --> adds execute permission to all subdirectories of current dir for all users without affecting file permissions
12-directory_permissions --> creates a new directory with set 751 permissions
13-change_group --> changes group owner for file hello
14-change_owner_and_group --> changes group and owner for all files and directories in current directory
15-symbolic_link_permissions --> changes group and owner for file linked by symbolic link
16-if_only --> changes owner of hello only if it's owned by specific users
