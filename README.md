# autotools_helloworld
HelloWorld for how to use autotools.

# Usage

## autoscan
Run the following command to produce templete for autoconf.
```bash
autoscan
```
Rename the output file configure.scan to configure.ac

## Configure templete for autoconf
Add the following needed define into configure.ac for automake.
```bash
AM_INIT_AUTOMAKE(helloword, 0.1)
```

## aclocal
Run the following command to export Macros from configure.ac to aclocal.m4 for automake
```bash
aclocal
```

## autoheader
Run the following command to produce templete config.h.in of config.h.
```bash
autoheader
```

## automake
Run the following command to produce templete Makefile.in of Makefile.
```bash
automake -a
```

## autoconf
Run the follwing command to produce the configure script for project.
```bash
autoconf
```


