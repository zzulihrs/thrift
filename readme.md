当前的目录文件结构如下
`-- thrift_lesson
    |-- game
    |   `-- src
    |-- match_system
    |   `-- src 
    |-- readme.md
    `-- thrift
        |-- match.thrift
        `-- save.thrift

(0) 进入thrift_lesson/match_system/src/目录，用cpp实现的match-server和save-client逻辑。
接口文件在thrift_lesson/thrift/中。
实现后启动server，监听端口9090。
(1) 进入thrift_lesson/game/src/目录，用python3实现的match-client逻辑。
