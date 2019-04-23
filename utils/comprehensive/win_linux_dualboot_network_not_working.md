1. Each `NIC` owns a unique `MAC`, hence the `MAC` is ingrained to the `NIC`.
2. Linux dows release `IP` before `shutdonw` where windows possesses it tightly for next use.
3. The way to make `dualboot` work is to release ip for `windows` before switching to `linux`.
4. In windows, open up `CMD` and type(__notice the space between ipconfig and /__) 
```
ipconfig /release    
```
