# https://mesonbuild.com/Tutorial.html

# install meson build tool
```
$ sudo apt install meson
```

# project setup
```
$ mkdir meson-build-tutorial/
$ cd meson-build-tutorial/
$ touch main.c meson.build
```

# 1 time build setup
```
$ meson setup builddir
```

# building (see previous section to create builddir)
```
$ cd builddir
$ ninja # or meson compile
```

# test
```
$ ./demo
```
