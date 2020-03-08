#C++ 线程注入


编译 dll.cpp 为 dll：
g++ -shared -o dll.dll dll.cpp

编译 Inject.cpp 为 exe：
g++ Inject.cpp

执行 Inject.exe 注入DLL线程到 calc.exe 中

[已解决]目前遇到的问题：注入的DLL并没有执行
感谢 @ysc3839 在过程中对我的帮助