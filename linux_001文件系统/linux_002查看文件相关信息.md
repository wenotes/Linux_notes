# linux查看文件相关信息

查看文件内容
```
cat a.txt           一次性输出文件中所有内容到界面
more a.txt          慢慢输出文件内容到界面，并显示进度
less a.txt          可以用鼠标滚动条滑动查看
head -行数 a.txt    显示文件前几行，默认10行
tail -行数 a.txt    显示文件末尾几行，默认10行
tail -f a.txt       一般用于看日志持续不断的输出（可简写tailf a.txt）


补充：高亮显示
    less a.txt 之后输入“/要高亮的字符”



```

查看文件编码格式

```
file a.txt
```