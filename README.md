# query_fofa_for_cnvd
**本项目已解决fofa签名问题！！！**

通过在fofa上搜索可能存在通用产品的公司，原理是判断网站标题数目以及独立IP数达到一定条件时将该标题以及公司名称导出。

如果想挖掘cnvd证书，可导出注册资金大于5000w的公司名称到`company.txt`文件中，使用这个脚本收集通用系统。

本项目使用了免费代理池项目作为支撑，代理池项目地址：https://github.com/jhao104/proxy_pool

完成代理池部署后，安装第三方库

`pip install -r requirements.txt`

然后将公司名称存入`company.txt`文件，启动脚本程序

`python query_fofa_for_cnvd.py`

结果将保存到`result.xlsx`文件中

**可根据需要修改第`118`行的搜索内容**

本项目参考：https://github.com/RaiderZP/cnvd_fofa_gather
