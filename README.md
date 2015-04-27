2D-Image and Texture Filter
===========================
**WARNING: This is a heavily modified fork of [https://code.google.com/p/2dimagefilter/](https://code.google.com/p/2dimagefilter/).**

I removed all G(UI) and any exotic (WPF, etc) .NET features that Mono does not support.

The command-line version is fully functional and can be used without any hickups.

```bash
ImageResizer /load in.png /resize auto "XBR 4x(2,thresholds=0,vbounds=wrap)" /save out.png
```

Depedencies
-----------
* Mono / NET 4.5

Contribute
----------
* Fork the project.
* Make your feature addition or bug fix.
* Do **not** bump the version number.
* Send me a pull request. Bonus points for topic branches.

Credits
-------
* 2dimagefilter / ImageResizer (Hawkynt)
* Eagle (the godfather himself)
* Super Eagle (thanks Kreed and ZSNES)
* SaI2x, Super2xSaI (also Kreed and DOSBox)
* Scale2x, Scale3x (thanks MAME for these)
* AdvInterp2x, AdvInterp3x (also MAME)
* HQ2x, HQ3x, HQ4x (Maxim Stepin)
* LQ2x, LQ3x, LQ4x (AFAIK SNES9x but AdvMAME also)
* HQ2x3, HQ2x4, LQ2x3, LQ2x4 (AdvMAME again)
* nQx Bold and Smart Version (SNES9x, VirtualBoyAdvance)
* Bilinear Plus Original and Modified (VBA-rr)
* XBR2x, XBR3x, XBR4x Normal and NonBlend (thanks Hyllian)
* Resampling kernels (Pascal Getreuer)
* XBRz (Zenju)
* SCL, DES (FNES)

License
-------
2dimagefilter / ImageResizer is provided **as-is** under the **GPLv3** license.
For more information see LICENSE.
