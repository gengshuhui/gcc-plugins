cgdb --args gcc -fplugin=./callbacks.so -x c -c test.c 
b plugin_init
set follow-fork-mode child
r
