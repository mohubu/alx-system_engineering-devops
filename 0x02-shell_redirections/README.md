# 0x02. Shell, I/O Redirections and filters


Shell, I/O Redirections, and Filters are essential concepts in the Unix/Linux command-line environment that allow for efficient data processing and manipulation. I/O (Input/Output) redirections allow you to control where the input comes from and where the output goes. They enable you to redirect the standard input, standard output, and standard error of a command or a pipeline of commands. 

## Files


| Filename | Description |
| -----------------------|-----------------------------------|
| `0-hello_world` | A script that prints "Hello,World", followed by a new line to the standard output. |
| `1-confused_smiley` | A script thatdisplaysa confused smiley "(Ôo)'. |
| `2-hellofile` | A script that displays the content of the `/etc/passwd` file. |
| `3-twofiles` | A script that displays the content of `/etc/passwd` and `/etc/hosts`. |
| `4-lastlines` | A script that displays 10 lines of `/etc/passwd`. |
| `5-firstlines` | A script that displays the first 10 lines of `/etc/passwd`. |
| `6-third_line` | A script that displays the third line of the fule `iacta`. |
| `7-file` | a scriptthat creates a file named exactly `\*\\'"Best School"\'\\*$\?\*\*\*\*\*:)` containing the text `Best School` ending by a new line. |
| `8-cwd_state` | A script that writes into the file `ls_cwd_content` the result of the command `ls -la`. If the file `ls_cwd_content` already exists, it should be overwritten. If the file `ls_cwd_content` does not exist, create it. |
| `9-duplicate_last_line` | A script that duplicates the last line of the file `iacta`. |
| `10-no_more_js` | A script that deletes all the regular files (not the directories) with a `.js` extension that are present in the current directory and all its subfolders. |
| `11-directories` | A script that counts the number of directories and sub-directories in the current directory. |
| `12-newest_files` | A script that displays the 10 newestfiles in the current directory. |
| `13-unique` | A script that takes a list of words as input and prints only words that appear exactly once. |
| `14-findthatword` | A script that displays lines containing the pattern `"root"` from the file ` /etc/passwd`. |
| `15-countthatword` | A script that displays the number of lines that contain the pattern"bin" in the file `/etc/passwd`. |
| `16-whatsnext` | A script that displays lines containing the pattern "root" and 3 lines after them in the file `/etc/passwd`. |
