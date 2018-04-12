# rcfiles
my setting files

## .zplugrc
read my zplug 

### write in ~/.zshrc 
``` 
source ~/.zplug/init.zsh
zplug "utwrd/rcfiles", use:.zplugrc, hook-load:"zplug load --verbose"
zplug load --verbose
``` 
## proxy
```
zplug "utwrd/rcfiles" use:proxy.sh
```
