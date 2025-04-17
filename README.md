# wxrecord
微信发布记录数据采集，用于数据统计。

## 安装
``` bash
pip install -r requirements
playwright install
```
## 运行步骤
- python test.py
- 登录、扫描二维码
- 打开“微信发布记录”
- 注意，等待1分钟后自动开始采集
- 数据将保存在根目录，EXCWL文件
