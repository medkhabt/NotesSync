# Idea 
I want to sync my notes between different machines. 
AT first, I tried to ssh to the remote machine of passau, so i only 
have to change the files one time, but the issue with this is that whenever
i want to open a pdf file or image or a tool that needs graphics, i need 
to transfer the files with scp. 
This repo is just to automize this stuff. I still want to have a centralized 
server, in this case the remote machine in uni passau. 

# Setup 
For this quick implementation, just add the two scripts "pullSync" and "pushSync" 
in a dir in your path env variable. 
Add 
``` bash 
export serverSsh="{username}@{domain}"
export pathServer="{path}" # without the last slash / for the dirs.  
```

# TODO 
- [X] synchronize notes action. 
- [X] synch by vim. 


