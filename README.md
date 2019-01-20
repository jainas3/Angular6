# Angular6 Project in Local PC
This repository is for angular 6 project (fullstack)
Steps for setup:
1) check your operating system properties 32/64 bit os? my computer --> right click --> properties accordingly download git
2) https://git-scm.com/download/win - download git for windows click "additional icon on desktop" while installing
3) https://nodejs.org/en/download/ download node js for windows click "add to path " while installing 
4) verify in "edit system environment variable" as below 
 it should have git , npn,node in both 
 1:user variable for username --> PATH
 C:\Program Files\nodejs\npm;C:\Program Files\Git\usr\local;C:\Program Files\Microsoft VS Code\bin;D:\Microsoft VS Code\bin
 2:system variable --> path 
C:\oraclexe\app\oracle\product\10.2.0\server\bin;C:\Program Files (x86)\AMD APP\bin\x86_64;C:\Program Files (x86)\AMD APP\bin\x86;%SystemRoot%\system32;%SystemRoot%;%SystemRoot%\System32\Wbem;%SYSTEMROOT%\System32\WindowsPowerShell\v1.0\;C:\Program Files (x86)\Intel\OpenCL SDK\2.0\bin\x86;C:\Program Files (x86)\Intel\OpenCL SDK\2.0\bin\x64;C:\Program Files\Git\cmd;C:\Program Files\nodejs\

Note: it should have git ,npm,node path .



5) check whether node / npm installed on your machine by opening git bash -->  node --version,npm --version

6) refer https://angular.io/guide/quickstart for angular installation
a: open cmd n install --> npm install -g @angular/cli
7) install visual studio code https://code.visualstudio.com/docs/?dv=win

