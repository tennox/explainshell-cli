### explainshell-cli


###### explainshell.com CLI implementation in Rust
_____________


##### Try it out:  
```nix shell github:tennox/explainshell-cli```  

##### Installation:  
Use your favorite way to install nix packages, or simply:
```nix profile install github:tennox/explainshell-cli```  

#### Usage:  
```explain COMMAND [ARGS]``` (combining arguments works)

##### Example:  
``` explain tar -xzvf```

##### Output:

```
The GNU version of the tar archiving utility
__________________________________________________

-x, --extract, --get
      extract files from an archive
__________________________________________________

-z, --gzip, --gunzip --ungzip
__________________________________________________

-v, --verbose
      verbosely list files processed
__________________________________________________

-f, --file ARCHIVE
      use archive file or device ARCHIVE
__________________________________________________
```
