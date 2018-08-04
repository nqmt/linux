# Linux Command

## tar

### Create

```tar <option> <file name to be  archive> <place to>```

with foder

```tar cvf example-tar-set-filename.tar ./tar```

each files & compress with gzip

```tar czvf example-tar-set-filename.tar ./tar/1.txt ./tar/2.txt```

### Extract

```tar xvf example-tar-set-filename.tar```

### Note

```
c - create
v - verbose (show list file process)
f - filename
x - extract
z - compress gzip
```

!!! Order option is important
```
tar cfv !== tar fvc
```


