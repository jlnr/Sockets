# Sockets

This is a set of wrapper classes around the BSD sockets API, ported from Delphi to C++ around 2004. They were part of the [Gosu library](https://libgosu.org/) until version 0.10.0, when I decided to remove them for several reasons:

* Lack of interest
* No progress, line-based communication is still broken
* No security, it is probably easy to DDOS/trigger buffer overflows with this
* Gosu should be lean and mean, not a kitchen sink library

If you actually *miss* this library, [let me know](mailto:julian@raschke.de)!

## Credits

The example was kindly contributed to Gosu by @oli-obk.
