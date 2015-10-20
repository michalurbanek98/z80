**Arduino driven Z80 development**

***Prerequisites***

There is actually a Z80 assembler in the universe repos!!!

```
sudo apt-get install z80asm 
```

will work on Ubuntu. Otherwise make sure z80asm is in your executable path. There is also a de-assembler for binaries (z80dasm).

***Assemble and generate Arduino code***

```
python assemble.py -i test.asm
```


In order to review binary hex code install bless:

```
sudo apt-get install bless
```

Notes:

Linux programmer for EPROM programmer

https://github.com/vdudouyt/minipro