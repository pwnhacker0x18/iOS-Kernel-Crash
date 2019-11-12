# CVE-2018-4407-Memory Corruption
The vulnerability is a heap buffer overflow in the networking code in the XNU operating system kernel. XNU is used by both iOS and macOS, which is why iPhones, iPads, and Macbooks are all affected. My exploit PoC just overwrites the heap with garbage, which causes an immediate kernel crash and device reboot.
