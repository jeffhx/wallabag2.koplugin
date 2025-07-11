# wallabag2.koplugin

Home page https://github.com/clach04/wallabag2.koplugin

A KoReader plugin for Wallabag (version 2) servers.

Makes use of the REST API documented at https://app.wallabag.it/api/doc/

See https://github.com/koreader/koreader/issues/10738 for background,
basically this plugin should be faster and better suited to modern wallabag instances.

## Installation

Copy the `wallabag2.koplugin` to the koreader `plugins` directory.

  * Under Android, local/koreader/plugins
  * Under Kindle, /koreader/plugins (under Windows mount `D:\koreader\plugins`)

Requires KoReader to be restarted.

Plugin will show up as, `NEW: WallabagX`, on (top) left hand menu for:

  * for file browser view, file system
  * for book reader view, bookmarks

## Usage

Same as Wallabag(1) plugin, see https://github.com/koreader/koreader/wiki/Wallabag

NOTE Uses the **same** config file (at least for now) as existing wallabag plugin!
I.e. `/koreader/settings/wallabag.lua`.

## Debugging

  * need either a [real Wallabag server](https://github.com/wallabag/wallabag) or (semi) compatible one such as:
      * https://github.com/clach04/whatabagacack
      * https://github.com/LordEidi/wombag
  * https://koreader.rocks/doc/topics/Hacking.md.html
  * enable debug log https://github.com/koreader/koreader/issues/2530#issuecomment-500866288 - `Developer options`, `Enable debug logging` - goes to `crash.log`
