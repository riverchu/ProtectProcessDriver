# ProtectProcess

工程迁移至[riverchu](https://github.com/riverchu)

驱动级内核进程保护，通过钩子控制两个与杀死进程有关的SSDT函数，和一个隐藏函数——杀死线程函数。
如此操作之后便可以同时保护和杀死任一进程。
