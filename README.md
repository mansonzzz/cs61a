# unlocking tests

```shell
alias py='python3'
```
---
`--local`无需邮箱验证
```shell
py ok -q python-basics -u --local
```
---
检测结果
```shell
py ok --local
```
---
使用`-i`可运行`Python`脚本，并打开一个交互式会话
```shell
py -i lab00.py
```
---
`-m doctest`在一个特定的文件中运行测试
```shell
py -m doctest lab00.py
```
