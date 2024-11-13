# password_shamir
Shamir 密码分片和助记词生成

Shamir加密

# 功能

# 生成助记词

使用bip39 随机生成助记词，完全开源，可以下载离线使用，确保安全。

# 加密指定内容

留空则生成随机助记词，加密后可以将加密后的内容交给不同人，或不同的地方分开保存。只有同时拥有设定的解密所需份数 (N) 密文才可以完成解密。假设 设定M=5 N=3 也就是说同时需要3份密文即可解密。

# 使用方法-加密

1.输入要加密的内容

2.输入 生成密文总数 (M)： 解密所需份数 (N)：

3.开始加密  会将需要加密的内容 加密为M份 集齐其中的N份 即可 解密。

## 注意：

---

加密后的内容 一定要分开存放 妥善保管 防止泄露。

加密后的内容 一定要分开存放 妥善保管 防止泄露。

加密后的内容 一定要分开存放 妥善保管 防止泄露。

---

# 使用方法-解密

将加密后的密文 输入到解密 输入框中。

集齐N份密文 即可解密。


# 安全提示：

- 只要加密后的密文分开妥善存放  确保绝对隔离  可以确保100%安全。

- 安全期间 加密后的密文 自己可以更改一两位，  但要自己一定要记得怎么改的，原来的是什么。
  
- 这样即使别人拿到了全部密文【你自己修改过的】 他也无法解密。 可以说是双保险。但风险是你自己也忘记了密文。那就无法解密了。
