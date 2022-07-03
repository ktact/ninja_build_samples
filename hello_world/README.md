# Hello, Ninja!
## Build
```bash
$ ninja -C .
ninja: Entering directory `.'
[2/2] cc  hello.o  -o hello
```
## Execute
```bash
$ ./hello
Hello, World!
```
## Clean
You can perform `clean` with the built-in options as follows.
```bash
$ ninja -t clean
Cleaning... 2 files.
```
