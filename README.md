Libhijack - FreeBSD Code Injection Swiss Army Knife
===================================================

Libhijack is a tool that enables easy injection of arbitrary code
during runtime. Injection is done into newly-created anonymous memory
mappings, providing stealth. An API is provided for hooking the
PLT/GOT, hence the "hijack" part of libhijack.

Building libhijack
==================

```
# make depend all install
```
