# no

Unix has `/usr/bin/yes` but it lacks `/usr/bin/no`.  We should fix that and this code does. 

## Output

```
n
n
n
n
n
n
n
n
...
Ctrl-C
```

## Building

Assuming you have go installed simply run:

    go build main.go 
    mv main /usr/bin/no

## FAQ

Some frequently asked questions... 

### Is this useful?

Probably not. 

