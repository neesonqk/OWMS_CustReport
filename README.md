EasyReport
==========

[1.0用户参考]: https://github.com/xianrendzw/EasyReport/blob/master/docs/manual/version1_0.md
[2.0用户参考]: https://github.com/xianrendzw/EasyReport/blob/master/docs/manual/version2_0.md
[支付宝]: https://raw.githubusercontent.com/xianrendzw/EasyReport/master/docs/assets/imgs/alipay-code.png


Compilation
===========
Manually register jdbc driver for mssql and oracle

mvn install:install-file -Dfile=/Users/neeson/Development/OWMS_CustReport/lib/sqljdbc42.jar -DgroupId=com.microsoft.sqlserver -DartifactId=sqljdbc4 -Dversion=4.0 -Dpackaging=jar

mvn install:install-file -Dfile=/Users/neeson/Development/OWMS_CustReport/lib/ojdbc6.jar -DgroupId=com.oracle -DartifactId=ojdbc6 -Dversion=11.2.0.3 -Dpackaging=jar
