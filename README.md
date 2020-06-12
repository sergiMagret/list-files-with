# lfw (List Files With)
**Warning, currently the program only lists directories**

`lfw [-d] [-p] [-o] [-n] [-s]`  
* `-d` initialDirectory: Indicates from which directory the script should start searching.  
If it's not set, starts with the actual directory.

* `-p` permissions: Indicates which permissions should be looked for, lfw at this version only lists directories, so a good format of permissions to search for would start with "d---------".  
If not set, searches for permissions "drwxrwxrwx".

* `-o`: Indicates if the hidden directories should be searched or not, the hidden directories are the ones that start with '.'.  
If not set, script does NOT search in hidden directories.

* `-n` owner: Indicates who owns the directories listed/searched.  
If not set lists directories with any owner.

* `-s` file: Indicates to which file the output shoud be redirected to, the script can also be called without	this parameter and use the redirection "> file".  
If not set, the output is shown on console.
