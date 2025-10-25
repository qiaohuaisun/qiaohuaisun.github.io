# FAQ（常见问题）

> 本 FAQ 汇总了在学习计算机过程中的常见问题，持续更新中。

## Q1: 装了环境还是跑不起来？

**A:** 排查步骤：
1. **提供完整信息**：
   - 操作系统（Windows 10/11, macOS, Linux）
   - 编程语言版本（Python 3.11, Java 17 等）
   - 报错的完整信息（截图或复制文本）
   - 最小可复现代码（几行能重现问题的代码）

2. **常见问题**：
   - **环境变量未配置**：检查 PATH 是否包含相关路径
   - **版本不兼容**：查看文档要求的版本
   - **权限问题**：以管理员身份运行
   - **端口占用**：换个端口或关闭占用进程

3. **寻求帮助**：
   - 在 Stack Overflow 搜索错误信息
   - 在相关技术群提问
   - 在 GitHub Issue 中查找类似问题

---

## 如何提问

**好的提问方式**：
```
【问题】：运行 Python 程序报错 ModuleNotFoundError: No module named 'requests'
【环境】：Windows 11, Python 3.11
【已尝试】：
1. 运行 pip install requests，提示 successfully installed
2. 重启了电脑
3. 检查了环境变量，Python 路径正确

【代码】：
import requests
response = requests.get('https://www.baidu.com')
print(response.text)

【报错信息】：
Traceback (most recent call last):
  File "test.py", line 1, in <module>
    import requests
ModuleNotFoundError: No module named 'requests'
```

**不好的提问方式**：
- "我的代码跑不了，怎么办？"（没有任何信息）
- "Python 报错了"（没有具体错误）
- "求大神帮忙"（没说什么问题）

---

## 更多问题？

- **提交 Issue**：在本项目 GitHub 仓库提交问题

**持续更新中，欢迎补充！**

---

**最后更新时间**：2025-10-20

