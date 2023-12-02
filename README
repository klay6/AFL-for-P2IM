# AFL-for-P2IM
- AFL version = afl-2.52b
- AFL_URL=AFL_URL=https://github.com/Fuzzers-Archive/afl-2.52b/archive/c49750c9e27e29100d055292453551d560e594ce.zip
- AFL Original README：docs/README
## usage
Follow the instructions of [p2im](https://github.com/RiS3-Lab/p2im)
### AFL
```
# Compile AFL
# Use
make -C AFL-for-P2IM/
# Instead of make -C afl/
```
> Test_build may fail when “Testing the CC wrapper and instrumentation output...”, but it does not affect much.
### Change the AFL path
Change the AFL path in fuzz.cfg，like：
```
[afl] # used only by fuzz.py
bin         = %(base)s/AFL-for-P2IM/afl-fuzz
```
