# linux-4.8.15

| 目录          | 描述 |
| ---           | --- |
|arch           |特定体系结构的源码|
|block          |块设备I/O层
|certs          |
|crypto         |加密API
|Documentation  |内核源码文档
|drivers        |设备驱动程序
|firmware       |使用某些驱动程序而需要的设备固件
|fs             |VPS和各种文件系统
|include        |内核头文件
|init           |内核引导和初始化
|ipc            |进程间通信代码
|kernel         |像调度程序这样的核心子系统
|lib            |通用内核函数
|mm             |内存管理子系统和VM
|net            |网络子系统
|samples        |示例
|scripts        |编译内核所用的脚本
|security       |Linux安全模块
|sound          |语音子系统
|tools          |在Linux开发中有用的工具
|usr            |早期用户空间代码（所谓的initramfs）
|virt           |虚拟化基础结构

|~结构体                |~位置                          |说明
|task\_struct           |linux/sched.h                  |进程描述符
|thread\_info           |asm/thread\_info.h             |
|sys\_call\_table       |arch/ia64/kernel/entry.S       |系统调用表
|list\_head             |include/linux/types.h, list.h  |链表

|~函数                  |~位置                              |说明
|copy\_from\_user       |arch/ia64/include/asm/uaccess.h    |从用户空间读取数据到内核空间
|copy\_to\_user         |arch/ia64/include/asm/uaccess.h    |从内核空间写数据到用户空间

|~术语          |描述
|smp            |对称多处理系统 Symmetric Multi Processing

|~文件          |功能
|kernel/sys.c   |定义常用的系统调用
|include/uapi/asm-generic/unistd.h      |定义系统调用号
