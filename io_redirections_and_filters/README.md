# I/O Redirections and Filters

This project contains Bash scripts that demonstrate shell commands, input/output redirection, and filters.

## Scripts

- `0-hello_world`: Prints "Hello, World" followed by a new line.
- `1-confused_smiley`: Displays a confused smiley.
- `2-hellofile`: Displays the contents of `/etc/passwd`.
- `3-twofiles`: Displays the contents of `/etc/passwd` and `/etc/hosts`.
- `4-lastlines`: Displays the last 10 lines of `/etc/passwd`.
- `5-firstlines`: Displays the first 10 lines of `/etc/passwd`.
- `6-third_line`: Displays the third line of the file `iacta`.
- `7-file`: Creates a file with a special name containing `Best School` followed by a new line.
- `8-cwd_state`: Saves the output of `ls -la` to `ls_cwd_content`, overwriting it if it exists.
- `9-duplicate_last_line`: Duplicates the last line of `iacta`.
- `10-no_more_js`: Deletes regular `.js` files in the current directory and its subdirectories.
- `11-directories`: Counts all directories and subdirectories, including hidden directories.
- `12-newest_files`: Displays the 10 newest entries in the current directory, newest first.
- `13-unique`: Prints words that appear exactly once, sorted alphabetically.
- `14-findthatword`: Displays lines containing `root` from `/etc/passwd`.
- `15-countthatword`: Counts lines containing `bin` in `/etc/passwd`.
- `16-whatsnext`: Displays lines containing `root` and the three following lines from `/etc/passwd`.
- `17-hidethisword`: Displays lines from `/etc/passwd` that do not contain `bin`.
- `18-letteronly`: Displays lines from `/etc/ssh/sshd_config` that start with an uppercase or lowercase English letter.
- `19-AZ`: Replaces every `A` with `Z` and every `c` with `e` in the input.
- `20-hiago`: Removes all lowercase `c` and uppercase `C` characters from input.
- `21-reverse`: Reverses the characters in each input line.
