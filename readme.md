# ZigLinux: The Hybrid Kernel Revolution

>  Why choose between safety and performance? We chose both.

- ZigLinux is an experimental, high-performance operating system kernel that pushes the boundaries of modern systems programming. It features a hybrid architecture combining the memory safety and metaprogramming power of Zig, the expressiveness of modern C++, and the rapid development capabilities of Nim for critical tooling and bootloaders.
- Built from the ground up by Belbel, this project aims to prove that the future of OSDev lies in multi-language ecosystems working in harmony.
## Key Features

-    Zig Core: Memory management, scheduler, and interrupt handlers written in Zig for zero-overhead safety and comptime magic.
-   C++ Subsystems: Complex drivers (GPU, Networking) and filesystems leveraging modern C++20 templates and RAII without runtime bloat (-fno-exceptions).
-   Nim Tooling & Bootloader: The build system, UEFI bootloader (JuiceBoot), and high-level utilities are crafted in Nim, utilizing its powerful macros and clean syntax for freestanding environments.
-   JuiceScript Integration: A custom scripting language (Lexer/Parser/VM included) embedded directly into the kernel for dynamic runtime configuration.
-   Hybrid ABI: Seamless interoperability between Zig, C++, and C via a unified global allocator and strict extern "C" bridges.

