## 操作系统实验五：简单文件系统



### 已完成的工作
- 第一部分基本完成


### 工作进度
- 正在写my_open，进入do_read分析并编写
- 基本完成了my_open,my_read,do_read,正在写my_mkdir
- my_mkdir写了在当前目录下建立目录,通过路径来建立还没写
- my_ls显示格式还没完善，并且创建的根目录下的"."和".."有问题
- my_mkdir出现问题，大概是因为没有实现do_write(),现在开始实现do_write()和my_write()
- do_write()和my_write()还需要分析，另外其中的gets()之后应该优化为fgets()
- 打开文件和关闭文件时应该打印出对应的fd
- my_close()的返回值与在线平台有出入
- 当前目录的内容是否应该存在内存中？
- 实现了my_ls()，现在只剩下my_create()和my_rm()以及一些问题
- my_create()中是否需要将新建立的文件打开
- 基本完成了所有函数，但是有很多与在线平台不符合，以及一些错误，需要修改

- 发现一个bug：不在根目录输入my_exitsys会一直打印my_close: fd无效