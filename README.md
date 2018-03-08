# generic-lens-example

```
$ stack build
Building all executables for `generic-lens-example' once. After a successful build of all of them, only specified executables will be rebuilt.
generic-lens-example-0.1.0.0: build (exe)
Preprocessing executable 'generic-lens-example' for generic-lens-example-0.1.0.0..
Building executable 'generic-lens-example' for generic-lens-example-0.1.0.0..
[1 of 2] Compiling Examples         ( src/Main.hs, .stack-work/dist/x86_64-linux-nopie/Cabal-2.0.1.0/build/generic-lens-example/generic-lens-example-tmp/Examples.o )

/home/kb/workspace/generic-lens-example/src/Main.hs:20:1: error:
    Could not find module ‘Data.Generics.Internal.VL.Lens’
        Perhaps you meant
              Data.Generics.Internal.Lens (from generic-lens-0.5.1.0)
                    Data.Generics.Internal.HList
                          Data.Generics.Internal.Void
                              Use -v to see a list of the files searched for.
                                 |
20 | import Data.Generics.Internal.VL.Lens
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

/home/kb/workspace/generic-lens-example/src/Main.hs:24:1: error:
    Could not find module ‘Data.Generics.Labels’
        Use -v to see a list of the files searched for.
           |
24 | import Data.Generics.Labels
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^

/home/kb/workspace/generic-lens-example/src/Main.hs:25:1: error:
    Could not find module ‘Data.Generics.Internal.VL.Iso’
        Perhaps you meant
              Data.Generics.Internal.HList
                    Data.Generics.Internal.Lens (from generic-lens-0.5.1.0)
                          Data.Generics.Internal.Void
                              Use -v to see a list of the files searched for.
                                 |
25 | import Data.Generics.Internal.VL.Iso
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

/home/kb/workspace/generic-lens-example/src/Main.hs:26:1: error:
    Could not find module ‘Data.Generics.Internal.VL.Prism’
        Perhaps you meant
              Data.Generics.Internal.HList
                    Data.Generics.Internal.Lens (from generic-lens-0.5.1.0)
                          Data.Generics.Internal.Void
                              Use -v to see a list of the files searched for.
                                 |
26 | import Data.Generics.Internal.VL.Prism
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

/home/kb/workspace/generic-lens-example/src/Main.hs:27:1: error:
    Could not find module ‘Data.Generics.Internal.Profunctor.Lens’
        Use -v to see a list of the files searched for.
           |
27 | import Data.Generics.Internal.Profunctor.Lens
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

/home/kb/workspace/generic-lens-example/src/Main.hs:28:1: error:
    Could not find module ‘Data.Generics.Internal.Profunctor.Iso’
        Use -v to see a list of the files searched for.
           |
28 | import Data.Generics.Internal.Profunctor.Iso
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

/home/kb/workspace/generic-lens-example/src/Main.hs:29:1: error:
    Could not find module ‘Data.Generics.Internal.Profunctor.Prism’
        Use -v to see a list of the files searched for.
           |
29 | import Data.Generics.Internal.Profunctor.Prism
   | ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^


--  While building custom Setup.hs for package generic-lens-example-0.1.0.0 using:
      /home/kb/.stack/setup-exe-cache/x86_64-linux-nopie/Cabal-simple_mPHDZzAJ_2.0.1.0_ghc-8.2.2 --builddir=.stack-work/dist/x86_64-linux-nopie/Cabal-2.0.1.0 build exe:generic-lens-example --ghc-options " -ddump-hi -ddump-to-file -fdiagnostics-color=always"
          Process exited with code: ExitFailure 1
```
