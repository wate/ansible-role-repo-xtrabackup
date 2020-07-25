xtrabackup
=========

[![Build Status](https://travis-ci.org/wate/ansible-role-xtrabackup.svg?branch=master)](https://travis-ci.org/wate/ansible-role-xtrabackup)

[Percona XtraBackup](https://www.percona.com/software/mysql-database/percona-xtrabackup)のインストールとセットアップを行います

※Percona XtraBackupの利用方法は[公式ドキュメント](https://www.percona.com/doc/percona-xtrabackup/2.4/index.html)を参照してください。

Role Variables
--------------

### xtrabackup_version

インストールするPercona XtraBackupのパッケージバージョンを指定します。

```yml
xtrabackup_version: 24
```

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - role: xtrabackup
```

License
-------

MIT
