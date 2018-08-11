# CentOS7 常用命令集合
#### 文件与目录操作
``` C#
cd /home					            进入 ‘/home’ 目录
cd ..						              返回上一级目录
cd ../..					            返回上两级目录
cd -						              返回上次所在目录
cp file1 file2				        将file1复制为file2
cp -a dir1 dir2				        复制一个目录
cp -a /tmp/dir1 .			        复制一个目录到当前工作目录（.代表当前目录）
ls							              查看目录中的文件
ls -a						              显示隐藏文件
ls -l						              显示详细信息
ls -lrt						            按时间显示文件（l表示详细列表，r表示反向排序，t表示按时间排序）
pwd							              显示工作路径
mkdir dir1					          创建 ‘dir1’ 目录
mkdir dir1 dir2				        同时创建两个目录
mkdir -p /tmp/dir1/dir2		    创建一个目录树
mv dir1 dir2				          移动/重命名一个目录
rm -f file1					          删除 ‘file1’
rm -rf dir1					          删除 ‘dir1’ 目录及其子目录内容
```
