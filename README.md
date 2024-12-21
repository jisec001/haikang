#### 海康威视综合安防管理平台 orgManage/v1/orgs/download 任意文件读取漏洞复现

![image-20241220153351984](C:\Users\lenovo\AppData\Roaming\Typora\typora-user-images\image-20241220153351984.png)

```
描述:海康威视综合安防管理平台/orgManage/v1/orgs/download 接口处存在任意 文件读取漏洞，未经身份验证的远程攻击者可利用目录遍历的方式绕过权限认证直接读取后台服务器配置文件等敏感文件，造成信息泄露，使系统处于极不安全的状态。
网络fofa: title="综合安防管理平台"
```

