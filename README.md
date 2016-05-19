# apklogger

An application to log all called functions of a selected application (similar to `strace`)

This can be done using :
 - Xposed Framework (current focus)
 - jdb (The Java Debugger)
 
# TODO
- [ ] List all running applications
- [ ] Wrapper to choose and launch an installed application
- [ ] List classes 
- [ ] List function prototypes (input parametrs, types, return value)
- [ ] List internal variables
- [ ] Log executed function calls
- [ ] Log network activities (new connections, opened ports, etc...)
- [ ] Log memory activities (memory allocations, free, etc...)
- [ ] Log IO activities (opened files, read/write, etc...)
- [ ] Log requested permissions
- [ ] Sandboxing
- [ ] Inline patching (smali, inject modules, etc...)
- [ ] Dumping (functions, classes, objects, etc...)
