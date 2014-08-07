# Example duplicate_symbol error code

## Background

When building on OSX you might see errors like this:

```
duplicate symbol _name in:
/var/folders/6x/vqbtyyvd5r136lb7hpb0qvmw0000gp/T/1-siEqxi.o
/var/folders/6x/vqbtyyvd5r136lb7hpb0qvmw0000gp/T/2-bMFgvM.o
ld: 1 duplicate symbol for architecture x86_64
clang: error: linker command failed with exit code 1 (use -v to see invocation)
make: *** [all] Error 1
```

## Origin

http://samwho.co.uk/blog/2013/12/08/duplicate-symbol-what/

