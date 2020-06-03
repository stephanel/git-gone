See [git gone: cleaning stale local branches](http://eed3si9n.com/git-gone-cleaning-stale-local-branches).

### license

MIT License


 - Store the bash script where you want (here: C:\users\<username>\)
 - Edit your .bashrc file and add the path to the PATH variable:
    ```console
    export PATH=$PATH:~/
    ```
- Open a Git bash and type the following command to ensure you see the usage instructions:
    ```console
    $ git gone
    ```
- Type the following commands to clean your local branches:
    ```console
    $ git gone -pn
    (...)
    $ git gone -d
    ```
- Type the following one if any branch failed to delete:
    ```console
    $ git gone -D
    ```


