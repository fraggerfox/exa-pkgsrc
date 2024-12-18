exa-pkgsrc
==========

NetBSD [pkgsrc][4] script for `exa`.

You can find `exa` [here][1]

**NOTE: This port has been [deprectated][5] and removed from the pkgsrc tree.**

Installation
------------

Copy `sysutils/exa` folder to `/usr/pkgsrc` directory.

NOTE: If your pkgsrc directory is different from above, copy to the respective
place.

Usage
-----

Once you have copied the folder, install it as you would do for any port.

`$ cd /usr/pkgsrc/sysutils/exa`<br>
`$ make install clean`

For a list of dependencies for the build check [here][2]

NOTE: If you are using pkgsrc in a non NetBSD system, replace `make` with
`bmake` in the above example.

Credits
-------

* `exa` is developed and maintained by the [Benjamin Sago][3]
* Thanks to `@coypoop` and `leot@` for reviewing and suggesting fixes to the
  package.

License
-------

BSD 2-clause. See LICENSE.

[1]: https://the.exa.website/
[2]: https://github.com/ogham/exa#installation
[3]: https://bsago.me/
[4]: http://pkgsrc.se/sysutils/exa
[5]: https://pkgsrc.se/files.php?messageId=20230911122023.1EB85FBDB@cvs.NetBSD.org
