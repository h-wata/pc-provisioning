## Setup

```
# インストール対象にssh公開鍵を渡す(事前のssh serverを入れておく)
$ ssh-copy-id -i ~/.ssh/id_rsa 192.168.xx.yyy
```

inventoryにインストール対象のIPを設定

```
# playbookコマンド
ansible-playbook -i inventory playbook.yaml -v
```


