This README describes what each script does:

0-prints “Hello, World”, followed by a new line to the standard output.
1-displays a confused smiley "(Ôo)'.
2-Display the content of the /etc/passwd file.
3-Display the content of /etc/passwd and /etc/hosts
4-Display the last 10 lines of /etc/passwd
5-Display the first 10 lines of /etc/passwd
6-displays the third line of the file iacta.
7-creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School ending by a new line.
8-writes into the file ls_cwd_content the result of the command ls -la. If the file ls_cwd_content already exists, it should be overwritten. If the file ls_cwd_content does not exist, create it.
9-duplicates the last line of the file iacta
10-deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.
11-counts the number of directories and sub-directories in the current directory.
	  The current and parent directories should not be taken into account
    	  Hidden directories should be counted
12-displays the 10 newest files in the current directory.
	  Requirements:
		One file per line
		Sorted from the newest to the oldest
13-takes a list of words as input and prints only words that appear exactly once.
	 Input format: One line, one word
	 Output format: One line, one word
	 Words should be sorted
14-Display lines containing the pattern “root” from the file /etc/passwd
15-Display the number of lines that contain the pattern “bin” in the file /etc/passwd
16-Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd.
17-Display all the lines in the file /etc/passwd that do not contain the pattern “bin”.
18-Display all lines of the file /etc/ssh/sshd_config starting with a letter.
	 include capital letters as well
19-Replace all characters A and c from input to Z and e respectively.
20-removes all letters c and C from input.
21-reverse its input.
22-displays all users and their home directories, sorted by users.
	 Based on the the /etc/passwd file
23-finds all empty files and directories in the current directory and all sub-directories.
	 Only the names of the files and directories should be displayed (not the entire path)
	 Hidden files should be listed
	 One file name per line
	 The listing should end with a new line
	 You are not allowed to use basename, grep, egrep, fgrep or rgrep
24-lists all the files with a .gif extension in the current directory and all its sub-directories.
	 Hidden files should be listed
	 Only regular files (not directories) should be listed
	 The names of the files should be displayed without their extensions
	 The files should be sorted by byte values, but case-insensitive (file aaa should be listed before file bbb, file .b should be list		ed before file a, and file Rona should be listed after file jay)
	 One file name per line
	 The listing should end with a new line
	 You are not allowed to use basename, grep, egrep, fgrep or rgrep
25-decodes acrostics that use the first letter of each line.
	 The ‘decoded’ message has to end with a new line
	 You are not allowed to use grep, egrep, fgrep or rgrep
26-parses web servers logs in TSV format as input and displays the 11 hosts or IP addresses which did the most requests.
	 Order by number of requests, most active host or IP at the top
	 You are not allowed to use grep, egrep, fgrep or rgrep
