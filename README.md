# bash-dracula-colors
For using custom bash consle you should download **.bashrc_colors** and copy to home directory
```shell
cd $HOMEDIR
wget https://raw.githubusercontent.com/myzed-ru/bash-dracula-colors/main/.bashrc_colors
```

After that you should add code to .bashrc file.
Follow code for installation:
```shell
if [ -f ~/.bashrc_colors ]; then
   . ~/.bashrc_colors
fi
```

After that you can load immediately.
```shell
source .bashrc
```

Result: <br>

![Example](src/img/console-example.png)