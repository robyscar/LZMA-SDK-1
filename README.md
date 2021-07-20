# LZMA-SDK
## All credits go to Igor Pavlov @ https://www.7-zip.org/

## This is a mirror of the original source code with bug fixes on top.
For details, check out the commit log


https://www.7-zip.org/sdk.html

LZMA SDK (Software Development Kit)
The LZMA SDK provides the documentation, samples, header files, libraries, and tools you need to develop applications that use LZMA compression.

Link	Size	Date	Version	Description
Download	1 MB	2021-05-06	21.02 alpha	LZMA SDK
C, C++, C#, Java
x86/x64 binaries for Windows
Download	1 MB	2019-02-21	19.00
Download	1 MB	2016-10-04	16.04
Download	12 KB	2015-06-14		LZMA Specification (Draft)
What's new:

21.02 alpha: macOS and Linux support. Speed optimizations.
19.00: Encryption strength for 7z archives was increased.
18.06: Some speed optimiztions in LZMA/LZMA2 code.
18.05: Some speed optimiztions in LZMA/LZMA2 code.
18.01: Some changes in LZMA2/xz multithreading code for compressing. Some bugs were fixed.
9.35: AES code and SFXs modules were included to SDK.
9.20: New small SFX module for installers.
9.11: PPMd support.
9.04: LZMA2 and XZ support.
4.62: LZMA SDK is placed in the public domain.
LZMA / LZMA2 are default and general compression methods of 7z format in the 7-Zip program. LZMA provides a high compression ratio and fast decompression, so it is very suitable for embedded applications. For example, it can be used for ROM (firmware) compressing.

LZMA SDK includes:

C++ source code of LZMA Encoder and Decoder
C++ source code for .7z compression and decompression (reduced version)
ANSI-C compatible source code for LZMA / LZMA2 / XZ compression and decompression
ANSI-C compatible source code for 7z decompression with example
C# source code for LZMA compression and decompression
Java source code for LZMA compression and decompression
lzma.exe for .lzma compression and decompression
7zr.exe to work with 7z archives (reduced version of 7z.exe from 7-Zip)
SFX modules to create self-extracting packages and installers
ANSI-C and C++ source code in LZMA SDK is subset of source code of 7-Zip.

LZMA features:

Compression speed: 3 MB/s on 3 GHz dual-core CPU.
Decompression speed:
20-50 MB/s on modern 3 GHz CPU (Intel, AMD, ARM).
5-15 MB/s on simple 1 GHz RISC CPU (ARM, MIPS, PowerPC).
Small memory requirements for decompression: 8-32 KB + DictionarySize
Small code size for decompression: 2-8 KB (depending on speed optimizations)
The LZMA decoder uses only CPU integer instructions and can be implemented for any modern 32-bit CPU.

License
LZMA SDK is placed in the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or distribute the original LZMA SDK code, either in source code form or as a compiled binary, for any purpose, commercial or non-commercial, and by any means.
