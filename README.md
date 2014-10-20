winproxy
========

Executable for manipulating Windows system proxy settings. This uses wininet and allows the setting of PAC files instead of winhttp that tools like netsh uses and that are more limited. Works on Windows XP and above.

You can call the following:

To set the PAC file url:
```
winproxy.exe -autoproxy "http://127.0.0.1/pac.url"
```

To set the proxy URL:
```
winproxy.exe -proxy "http://127.0.0.1/proxy"
```

To stop proxying:
```
winproxy.exe -unproxy
```
