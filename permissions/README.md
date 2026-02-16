This folder holds all scripts related to Permissions management in Shell.

| Filename                    | Action(s) summary                                                                                  |
| --------------------------- | -------------------------------------------------------------------------------------------------- |
| 0-iam_betty                 | Switches current user to 'betty'.                                                                  |
| 1-who_am_i                  | Prints the effective username of current user.                                                     |
| 2-groups                    | Prints all groups the current user is part of.                                                     |
| 3-new_owner                 | Switches ownership of file 'hello' to user 'betty'.                                                |
| 4-empty                     | Creates an empty file 'hello' in current directory.                                                |
| 5-execute                   | Gives owner of file 'hello' permission to execute it.                                              |
| 6-multiple_permissions      | Adjust permissions for owner and groups (+x) and others (+r) on file 'hello'.                      |
| 7-everybody                 | Allows everyone to execute 'hello' file.                                                           |
| 8-James_Bond                | Makes the file a true spy document permissions-wise (007!).                                        |
| 9-John_Doe                  | Redefines permissions for each "category" on file hello.                                           |
|10-mirror_permissions        | Mirrors the permissions of "olleh" file onto "hello" file.                                         |
|11-directories_permissions   | Recursively adds permission to execute on all subdirectories (note files) for everyone.            |
|12-directory_permissions     | Creates a directory with predefined set of permissions 751 in current dir.                         |
|13-change_group              | Attributes the 'hello' file's group ownership to group 'school'.                                   |
|14-change_owner_and_group    | Redefines user (vincent) and group (staff) ownership for all files and directories in current dir. |
|15-symbolic_link_permissions | Changes the ownerships of symbolic link underscorehello in current dir.                            |
|16-if_only                   | Checks the owner of file 'hello' is 'guillaume' and only then re-affects it to 'vincent'           |  

