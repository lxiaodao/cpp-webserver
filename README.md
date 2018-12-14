# cpp-webserver
A simple webserver for Windows

## 此版本特性
加入vs2015工程
服务器输出支持中文，进行utf-8编码转换
增加config.ini文件，服务器端口和crsf跨越参数加入配置文件
部分warning忽略

## Getting the sources from Github

    git clone https://github.com/ReneNyffenegger/cpp-webserver webserver
    cd webserver
    git submodule update --init --recursive

## Compiling & Running the Webserver

The suppliead `compile.mingw.bat` should compile the sources into `WebServer.exe`.

This executable, when started, listens on port 8080 (`http://localhost:8080`).

## See also

http://renenyffenegger.ch/notes/web/webserver/cpp/simple/index
