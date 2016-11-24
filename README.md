# powershell

## 编辑与调试
windows 下可通过Windows PowerShell ISE 编辑与调试，PowerShell 的文件扩展名为ps1，默认情况下系统无法直接运行ps1，可通过修改系统策略来实现，具体方法如下：
以administrator权限运行Windows PowerShell ISE 输入以下命令

```
Set-ExecutionPolicy Unrestricted
```

在弹出的选择框中选择yes即可
