# 聪明钱钱包地址批量转换器

## 背景

目前不同的平台有不同的钱包批量数据结构，主要包括空格式、冒号式和逗号式：

Diting：空格式

```
6c7CWNCSKvPMAbwZujh9b4Wf4yB6JehqSKncgXV6BE5T XQ
6EDJ7JuynXSPaMvufzAX4swSRJZXv6uPi4s6jmo33xj5 群主
```

GMGN：冒号式

```
3HGoswJWy9iYYJ4RHxte7T8H6HDsbdjghtCR76KQiHUT:AliceBCEiona,
6EDJ7JuynXSPaMvufzAX4swSRJZXv6uPi4s6jmo33xj5:Onefly.eth,
HGhMJZ2pztcxqzdkizdP3e5ECyo1j4gSmf6HQZwHy6vu:bigroot
```

Chain.fm：逗号式

```
XQ,6c7CWNCSKvPMAbwZujh9b4Wf4yB6JehqSKncgXV6BE5T
群主,6EDJ7JuynXSPaMvufzAX4swSRJZXv6uPi4s6jmo33xj5
```

## 功能

本脚本可以实现以下功能

- 根据提示选择当前输入的地址簿类型，粘贴，选择输出类型，输出转换结果

## 开发语言

使用Html和JavaScript开发，在单个网页完成，输入框，输出框以及类型选择按钮