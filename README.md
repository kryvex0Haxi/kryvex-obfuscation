# kryvex_lua-obfuscation

# KRYVEX

> A Rust-powered Lua Virtualization Obfuscator

Kryvex 是一个使用 Rust 开发的 Lua 虚拟化混淆器，专注于 Lua 字节码保护、虚拟化执行以及运行时防护。

---

## Supported Platforms

- Lua 5.1
- Lua 5.2
- Lua 5.3
- Lua 5.4
- Lua 5.5
- Luau
- Roblox

---

## Features

### Virtual Machine Protection

采用自定义虚拟化执行模型，对 Lua 字节码进行转换与保护。

### Multi-Version Support

兼容多个 Lua 版本以及 Luau 生态。

### Closure & Upvalue Support

支持复杂闭包与 Upvalue 生命周期管理。

### Compact Output

针对大型脚本进行了体积优化。

示例：

```text
Original Bytecode : 400 KB
Protected Output  : 200 KB
```

### Runtime Randomization

每次构建均生成不同的运行时结构与内部标识符。

---

## Architecture

```text
Lua Source
    │
    ▼
Bytecode Compiler
    │
    ▼
Intermediate Representation
    │
    ▼
Virtualization
    │
    ▼
Packing
    │
    ▼
Protected Script
```

---

## Current Status

| Item | Status |
|--------|--------|
| Development | Active |
| Language | Rust |
| License | All Rights Reserved |

---

## Repository

Kryvex is currently under active development.

The core virtualization technology remains proprietary and is not publicly released.

---

## Disclaimer

This repository is intended to showcase the project and development progress.

The core protection technology remains closed-source.

---

## License

All Rights Reserved.

Copyright © 2026 Kryvex.

No permission is granted to copy, modify, redistribute, sublicense, or create derivative works from this project without explicit authorization.
