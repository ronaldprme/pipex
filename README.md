# `pipex`

The purpose of this project is the discovery in detail UNIX mechanism - `pipe` and how process works.

### Discription of mandatory part
The program `pipex` should repeat the behaviour of the next shell command
```bash
$> < file1 cx file1 cmd1 cmd2
and looks like this:
```bash
$> ./pipex infile "cat" "hostname" outfile
$> ./pipex infile "ls -l" "wc -l" outfile

```
All errors like: wrong commands,  permission to files and etc, need be handle.
