# fun
There are some functions in Linux Bash.  
Shell scripts to help administer Linux servers.

For installation:
```
cd fun
for file in ./lib/*; do source $file; done
```

Example to check if a function has been loaded:
```
type :interface
```

Example to run.. Show network physical interfaces: 
```
:interface
```

To load functions automatically when you login, for example, you can add the command below to your ".bashrc" file:
```
for file in $HOME/fun/lib/*; do source $file; done
```


Thanks!
