# remote-pbcopy

This script is a wrapper on top of `pbcopy` command in Mac OSX. It copies the contents of a file from a remote server onto the OSX clipboard.

The usage is as below:

    ```
    ./rpbcopy -h remote_host -f remote_file_path

    remote_host: The hostname to copy file from
    remote_file_path: Full path of the file to be copied

    e.g. ./rpbcopy -h www.google.com -f '/bin/search'

    ```
