## Mac

**Build(compile) and Execute(run) C and C++**

`clang test.c -o test && ./test`

`clang++ -std=c++11 hello.cpp -o hello && ./hello`

## Ubuntu

`gcc test.c -o test && ./test`

`g++ -std=c++11 hello.cpp -o hello && ./hello`

* * *

## Debugging

- gdb(ubuntu) or lldb(mac)
- ddd(Data Display Debugger)
- nemiver

**Pull the debugger from the docker hub**

`docker pull dockerhub4manohar/ddd-nemiver-gui `

**Copy source file from host machine to docker container**

`docker cp hello.cpp ddd-GUI:/home/Cpp/`

**Start Data Display Debugger**

`ddd hello`

**Start Nemiver Debugger**

`nemiver`