# peer 版本

`peer version` 命令可以查看 peer 的版本信息。它会显示版本号、Commit SHA、Go 的版本、操作系统及架构和链码信息。例如：

```
 peer:
   Version: 1.4.0
   Commit SHA: 0efc897
   Go version: go1.11.1
   OS/Arch: linux/amd64
   Chaincode:
    Base Image Version: 0.4.14
    Base Docker Namespace: hyperledger
    Base Docker Label: org.hyperledger.fabric
    Docker Namespace: hyperledger
```

## 语法

```
Print current version of the fabric peer server.

Usage:
  peer version [flags]

Flags:
  -h, --help   help for version
```


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
