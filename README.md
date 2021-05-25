# class-dump-binaries
class-dump binaries for Objc and Swift apps

# Dump
## 可能代码，未验证
https://github.com/Maximus-/class-dump-swift
## 使用方法
https://www.programmersought.com/article/45381018640/

# 可信二进制结果
https://github.com/ivRodriguezCA/class-dump-binaries

# Inject

TODO: https://github.com/johnno1962/InjectionIII

https://theevilbit.github.io/posts/dyld_insert_libraries_dylib_injection_in_macos_osx_deep_dive/

## Code
```bash
binaries/class-dump-swift /Applications/WeChat.app/Contents/MacOS/WeChat  > wechat-origin.h

DYLD_INSERT_LIBRARIES=inject.dylib ./test
DYLD_INSERT_LIBRARIES=inject.dylib ls

```
