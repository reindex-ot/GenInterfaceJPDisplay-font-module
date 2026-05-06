#### GenInterfaceJP Display Font

Gen Interface JP Display font patch for Japanese users, based on the Mejiro Font Magisk module structure.

This build replaces the bundled Japanese font with Gen Interface JP Display 0.1.2 and keeps the dynamic `fonts.xml` generation used by the original module. It also redirects common Google Sans and Roboto file references to Gen Interface JP Display.

Changes in v1.1.0:

* Switches the module font from Gen Interface JP to Gen Interface JP Display.
* Redirects Google Sans and Roboto references in copied font XML files to Gen Interface JP Display.
* Uses Gen Interface JP Display Regular for OEM font files that are copied into the module overlay.

Changes in v1.0.1:

* Adjusted Google Sans customization handling to avoid stray dash-like glyphs in Google Search text.
* Extends the volume-key selection wait time during installation.

Supported installers:

* Magisk / Magisk forks using the standard module format
* KernelSU / KernelSU Next
* APatch

Supported Android targets:

* Android 11 and later, including current Android releases that keep the standard `/system/etc/fonts.xml` layout
* OEM font customizations handled by the original module, including Pixel/Google Sans, OnePlus/OxygenOS, OPLUS/ColorOS, Xiaomi/HyperOS, vivo, Sony, and related `fonts_customization.xml` variants

#### NOTICE

* Use the latest manager app for your root solution: Magisk, KernelSU, or APatch.
* KernelSU and APatch modules should be installed from their manager app, not from custom recovery.
* Magisk recovery flashing is retained through the standard `META-INF/com/google/android` installer files.

## License

- The module scripts remain licensed under [WTFPL](http://www.wtfpl.net/).
- GenInterfaceJP is licensed under the SIL Open Font License; see `LICENSES/OFL-GenInterfaceJP.txt`.

```
            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                    Version 2, December 2004

 Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>

 Everyone is permitted to copy and distribute verbatim or modified
 copies of this license document, and changing it is allowed as long
 as the name is changed.

            DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
   TERMS AND CONDITIONS FOR COPYING, DISTRIBUTION AND MODIFICATION

  0. You just DO WHAT THE FUCK YOU WANT TO.
```
