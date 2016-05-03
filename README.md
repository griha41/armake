armake
======

A C implementation of Arma modding tools (PAA conversion, binarization/rapification, PBO packing). (WIP)


### Setup

#### From Source

```
$ make
# make install
```

There are no dependencies other than a C lib with an fts library (like glibc) on \*nix systems.

#### Arch Linux

[PKGBUILD](https://aur.archlinux.org/packages/armake-git/)

Example (using pacaur):

```
$ pacaur -S armake-git
```


### Usage

See `$ armake --help` or [src/usage](https://github.com/KoffeinFlummi/armake/blob/master/src/usage).


### Credits

- [Mikero](https://dev.withsix.com/projects/mikero-pbodll) for his great documentation of the various file formats used.
- [T_D](https://github.com/Braini01) for great documentation, lots of pointers and even some code contributions
- [jonpas](https://github.com/jonpas) for all kinds of help with development and testing
- [kju](https://forums.bistudio.com/user/768005-kju/) for some pointers and "PR work"


### Used Libraries

- [docopt](https://github.com/docopt/docopt.c)
- [MiniLZO](http://www.oberhumer.com/opensource/lzo/)
- [STB's image libraries](https://github.com/nothings/stb)
- [Paul E. Jones's SHA-1 implementation](https://www.packetizer.com/security/sha1/)


### Disclaimer

This isn't official BI software. As such, it may not compile certain addons correctly or lag behind BI when new file format versions are introduced. As stated in the GPL, this software is provided without any warranty, so use at your own risk.


---

<p align="center"><a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=WQ55N7RKXUCF8"><img src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" style="max-width:100%;"></a></p>

<p align="center"><b>BTC</b> 1G3RbQr2JHeYDB8YGifkF42aaaMmjRKYyo</p>
