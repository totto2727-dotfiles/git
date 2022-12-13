# Usage

user.gitconfigの設定を行ってください

```gitconfig
[user]
email = # email
signingkey = # 公開鍵

[gpg "ssh"]
# 以下は1Passwordのパス
program = "/Applications/1Password.app/Contents/MacOS/op-ssh-sign"
```

allowed_signersの設定を行ってください

優先順位は上からになります

```allowed_signers
email 公開鍵
```
