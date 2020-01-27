# vsock-tools

This repository contains some tools for AF\_VSOCK on Linux:

* **vsock-get-cid.py** prints the local CID (guest or host)

## Examples

### vsock-get-cid.py
```shell
host$ sudo ./vsock-get-cid.py
Local CID: 2

guest$ sudo ./vsock-get-cid.py
Local CID: 42
```
