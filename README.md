## Initialized With

```
npm init -y
npm install rescript@10 -d
npm run dev
```

## Command Output

```bash
PS C:\Users\sebhe\Code\issue-rescript-permissions> npm run dev

> issue-rescript-permissions@1.0.0 dev
> rescript build -w

Error: EPERM: operation not permitted, open 'C:\Users\sebhe\Code\issue-rescript-permissions\.bsb.lock'
    at Object.openSync (node:fs:585:3)
    at acquireBuild (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:207:10)
    at build (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:516:11)
    at in_watch_mode (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:587:5)
    at ChildProcess.<anonymous> (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:317:9)
    at ChildProcess.emit (node:events:390:28)
    at maybeClose (node:internal/child_process:1064:16)
    at Process.ChildProcess._handle.onexit (node:internal/child_process:301:5) {
  errno: -4048,
  syscall: 'open',
  code: 'EPERM',
  path: 'C:\\Users\\sebhe\\Code\\issue-rescript-permissions\\.bsb.lock'
}
Error: EPERM: operation not permitted, open 'C:\Users\sebhe\Code\issue-rescript-permissions\.bsb.lock'
    at Object.openSync (node:fs:585:3)
    at acquireBuild (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:207:10)
    at build (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:516:11)
    at Timeout._onTimeout (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:544:11)
    at listOnTimeout (node:internal/timers:557:17)
    at processTimers (node:internal/timers:500:7) {
  errno: -4048,
  syscall: 'open',
  code: 'EPERM',
  path: 'C:\\Users\\sebhe\\Code\\issue-rescript-permissions\\.bsb.lock'
}
Error: EPERM: operation not permitted, open 'C:\Users\sebhe\Code\issue-rescript-permissions\.bsb.lock'
    at Object.openSync (node:fs:585:3)
    at acquireBuild (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:207:10)
    at build (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:516:11)
    at Timeout._onTimeout (C:\Users\sebhe\Code\issue-rescript-permissions\node_modules\rescript\rescript:544:11)
    at listOnTimeout (node:internal/timers:557:17)
    at processTimers (node:internal/timers:500:7) {
  errno: -4048,
  syscall: 'open',
  code: 'EPERM',
  path: 'C:\\Users\\sebhe\\Code\\issue-rescript-permissions\\.bsb.lock'
}
```

## System Info

```
OS Name:                   Microsoft Windows 11 Home
OS Version:                10.0.22000 N/A Build 22000
OS Manufacturer:           Microsoft Corporation
OS Configuration:          Standalone Workstation
OS Build Type:             Multiprocessor Free
System Manufacturer:       Microsoft Corporation
System Model:              Surface Laptop Studio
System Type:               x64-based PC
Processor(s):              1 Processor(s) Installed.
                           [01]: Intel64 Family 6 Model 140 Stepping 1 GenuineIntel ~3110 Mhz
BIOS Version:              Microsoft Corporation 18.101.141, 12/15/2021
```