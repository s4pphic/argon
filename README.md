# Argon

Argon is an experimental kernel and operating system derived from a mix of POSIX and NT ideals. As a kernel, it's of the [NT](https://en.wikipedia.org/wiki/Architecture_of_Windows_NT) lineage, without the fourty or so years that win32 and Windows have layered upon it. It keeps the genuinely good stuff such as;
 - The [Object Manager](https://en.wikipedia.org/wiki/Object_Manager)
 - The Executive services to separate kernel-land from userland
 - A human friendly Hardware Abstraction Layer (HAL)

Argon replaces the win32 usermode cruft with a lean, POSIX-like system with benefits of both merging together with little mayhem.
