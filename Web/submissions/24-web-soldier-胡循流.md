一.工具

1.开发者工具快捷键F12

2.hackbar插件

在浏览器中添加扩展插件
<img width="1404" height="612" alt="0151eadb195b62d8172234ba058337f5" src="https://github.com/user-attachments/assets/d74698af-8ead-4a50-bfa8-514f75025f81" />


3.python

用于编写并运行python脚本

4.AI：chatgpt,豆包，kimi

二.writeup

1.view_source

禁用右键就可以用F12查看源代码找到flag
<img width="1280" height="942" alt="image" src="https://github.com/user-attachments/assets/e47dd0b9-9110-4222-a84f-a32a428e1741" />

2.get_post

先用get方法提交一个值为1的变量a:在网址后面加上?a=1

再用post方法提交一个值为2的变量b:F12打开hackbar,在下面添加b=2,得到flag
<img width="1626" height="1145" alt="image" src="https://github.com/user-attachments/assets/7928ba85-213b-475b-a994-f43e779eb340" />

3.-用ai写一个python脚本，要求找到一个值经过md5加密后的前6位是15af95

<img width="1988" height="1007" alt="image" src="https://github.com/user-attachments/assets/47a668f6-25ab-4f88-b0a1-65064ffa7db1" />

<img width="1894" height="297" alt="image" src="https://github.com/user-attachments/assets/88b5a2bb-0cc0-4efb-8f4a-106e2bb625d4" />

该脚本通过循环递增数字，对每个数字的字符串形式计算MD5哈希，实时比对前6位是否为目标值，找到后立即输出结果并终止运行

三.Linux

Linux系统分为Linux系统内核和系统及应用程序，系统内核负责管理调度硬件

虚拟机：用虚拟化技术虚拟出电脑硬件，并给硬件安装操作系统，得到虚拟的系统环境

搭建Linux系统环境所需工具：下载VMware Workstation和Kali

<img width="1487" height="895" alt="4013ce0a7a29415df5cdd03f70242d59" src="https://github.com/user-attachments/assets/5efb36ef-fa3c-4ffc-ac71-75a85fcdd8b4" />

Linux常见命令

1. ls - 列出当前目录文件/目录

2. cd - 切换工作目录

3. pwd - 显示当前所在目录路径

4. mkdir - 创建新目录

5. rm - 删除文件/目录

6. cp - 复制文件/目录

7. mv - 移动/重命名文件

8. touch - 创建空文件或修改文件时间

9. cat - 查看文件全部内容

10. more - 分页查看长文件内容

11. less - 可上下滚动查看长文件

12. grep - 在文件中搜索指定字符串

13. find - 按条件查找文件

14. chmod - 修改文件/目录权限

15. chown - 更改文件/目录所有者

16. ps - 查看当前运行进程

17. kill - 终止指定进程

  




