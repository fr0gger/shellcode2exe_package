# X64 Shellcode2Exe Package

This tool is a compiled 64 bit executable for the tool [shellcode2exe](https://github.com/MarioVilas/shellcode_tools/blob/master/shellcode2exe.py). 
It allows to convert a shellcode in an executable file.

## Usage

```
Shellcode to executable converter
by Mario Vilas (mvilas at gmail dot com)

Usage:
        shellcode2exe.exe payload.bin [payload.exe]
                [--arch=i386|powerpc|sparc|arm]
                [--os=windows|linux|freebsd|openbsd|solaris]
                [-c Allow for ascii shellcode as a cmd line parameter]
                [-s Allows for ascii shellcode in file]
                [-d Allows for unicode shellcode as a cmd line parameter]
                [-u Allows for unicode shellcode in file]

Options:
  -h, --help            show this help message and exit
  -a ARCH, --arch=ARCH  target architecture [default: i386]
  -o OS, --os=OS        target operating system [default: windows]
  -c, --asciicmd        enable ascii entry in command line (e.g. -c '\x90\x90')
  -s, --asciifile       enable ascii entry in input file
  -d, --unicodecmd      enable unicode entry in command line (e.g. -d '%u9090')
  -u, --unicodefile     enable unicode entry in input file
  ```
