Both **#include** and **#import** request the preprocessor to read a file and add to its output.
#import can be considered as an improvised version of #include.
Objective-C prefers #import over #include. C developers tend to use #include over #import.

## The only difference is that:

1. **#include** allows us to include the **same file many times**.
2. **#import** makes sure that file is **included only once**.
