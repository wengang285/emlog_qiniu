1、将qiniu文件价copy到 $EMLOG_HOME/src/admin 目录下
2、用attlib.php覆盖$EMLOG_HOME/src/admin/views/attlib.php 目录
3、打开attachment.php文件，并在uploadQiNiu和deleteQiNiu函数中填入自己的七牛空间名，accessKey和secretKey，然后覆盖$EMLOG_HOME/src/admin/attachment.php
4、进入后台，写文章，就可以看到效果
5、只针对emlog_5.3.1，其他版本没有测试过