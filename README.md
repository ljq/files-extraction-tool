### Extract files based on file feature values (md5, sha256)

* **Hashs.xlsx**: Hash file verification value demo file:
    * md5
    * sha256
* **Results. xlsx**: File Content Extraction Information Result Set

### Configure&Build

    **Config.ini** configuration file:

###### dirToVerify: Directory of files awaiting extract

```
#Directory of Files Awaiting Censor
dirToVerify=verify-demo
```

###### Build: build command

```
# build linux platform:
env GOOS=linux GOARCH=amd64 go build -o ./bin/files-extraction-tool main.go
```

### Check Version

```
Usage:  -v|-V|--version: check current version
```

### Reference tool
* [xuri/excelize](github.com/xuri/excelize/v2)
