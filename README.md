GHC(STG,Cmm,asm) illustrated for hardware persons
=================================================

This is an illustrated document about the GHC(Glasgow Haskell Compiler).

Here is [haskell_ghc_illustrated.pdf](http://takenobu-hs.github.io/downloads/haskell_ghc_illustrated.pdf).


Contents
--------

- Executable binary
- Compile steps
- Runtime System
- Development languages
<br>

- Machine layer/models
- STG-machine
- Heap object in STG-machine
- STG-machine evaluation
- Pointer tagging
- Thunk and update
- Allocate and free heap objects
- STG - C land interface
<br>

- Boxity : boxed and unboxed
- Levity : lifted and unlifted
- Boxity and levity
<br>

- Thread
- Thread context switch
- Creating main and sub threads
- Thread migration
- Heap and Threads
- Threads and GC
- Bound thread
<br>

- Spark
<br>

- Mvar
- Software transactional memory
<br>

- FFI
- IO and FFI
- IO manager
<br>

- Bootstrap
<br>

- References
