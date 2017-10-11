# bash-hostfile
Simple script for managing local hostfile from CLI.

# Installation
```
curl https://raw.githubusercontent.com/kbentlage/bash-hostfile/master/hostfile -o /usr/local/bin/hostfile && chmod +x /usr/local/bin/hostfile
```

# Usage
## Listing current hostfile entries:
```
hostfile -l
```

## Add entry:
```
hostfile -a <hostname> <ip>
```

## Remove entry:
```
hostfile -r <hostname>
```
  
## Help:
```
hostfile -h
```
