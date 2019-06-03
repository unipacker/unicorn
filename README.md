Unicorn Engine: Un{i}packer Edition
===================================
[![PyPI: unicorn-unipacker](https://badge.fury.io/py/unicorn-unipacker.svg)](https://pypi.org/project/unicorn-unipacker/)

Unicorn is a lightweight, multi-platform, multi-architecture CPU emulator framework
based on [QEMU](http://qemu.org).

This fork provides a modified version of Unicorn
that handles access to the Windows [TIB](https://en.wikipedia.org/wiki/Win32_Thread_Information_Block).
Some binary packers want to read things from this block, so Un{i}packer needs to provide it.
Unicorn engine had this feature once, but it's not available in the current version. This is
why we created this fork that restores TIB functionality.

Unicorn offers some unparalleled features:

- Multi-architecture: ARM, ARM64 (ARMv8), M68K, MIPS, SPARC, and X86 (16, 32, 64-bit)
- Clean/simple/lightweight/intuitive architecture-neutral API
- Implemented in pure C language, with bindings for Crystal, Clojure, Visual Basic, Perl, Rust, Ruby, Python, Java, .NET, Go, Delphi/Free Pascal and Haskell.
- Native support for Windows & *nix (with Mac OSX, Linux, *BSD & Solaris confirmed)
- High performance via Just-In-Time compilation
- Support for fine-grained instrumentation at various levels
- Thread-safety by design
- Distributed under free software license GPLv2

Further information is available at http://www.unicorn-engine.org


License
-------

This project is released under the [GPL license](COPYING).


Compilation & Docs
------------------

See [docs/COMPILE.md](docs/COMPILE.md) file for how to compile and install Unicorn.

More documentation is available in [docs/README.md](docs/README.md).


Contact
-------

[Contact us](http://www.unicorn-engine.org/contact/) via mailing list, email or twitter for any questions.


Contribute
----------

If you want to contribute, please pick up something from our [Github issues](https://github.com/unicorn-engine/unicorn/issues).

We also maintain a list of more challenged problems in a [TODO list](https://github.com/unicorn-engine/unicorn/wiki/TODO).

[CREDITS.TXT](CREDITS.TXT) records important contributors of our project.

