# Interrogative Python
The patches in this repository, when applied on the proper CPython version, will make Python spit out every string pushed on the stack. This might be useful for deobfuscation, secret extraction and other nefarious or less nefarious purposes.

Note that the running code will be slower by about an order of magnitude.

If Interrogative Python segfaults, enters an endless loop, or crashes in any way on a program that works in vanilla Python, please open an issue. I wrote these patches in about an hour.
