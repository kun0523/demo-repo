# demo-repo

## subheader

tutorial about github

## gen ssh key:

- `ssh-keygen -t rsa -b 4096 -C "email/to/your/github/account"`  
  - `-t` 加密类型
  - `-b` 加密强度
  - `-C` github 的登陆名
  - `Enter file in which to save the key (C:\Users\wangy/.ssh/id_rsa): testkey` 输入密钥保存的文件名
- 在GitHub上配置自己的密钥  
  - `settings` >> `SSH and GPG keys`  >> 创建SSH Key >> 将 xxx.pub 中的密钥粘贴进来
- 将本地与GitHub关联
  - 