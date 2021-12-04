# About

* What is this repo?
> This is a slightly modified fork which includes some extra features added to my liking.
* How's this different from the main repo?

> * This repo comes with my RSS feed parser module **rss-chan** integrated. You'll never be late to your mirroring schedules now. You can read more about it [here](https://github.com/hyPnOtICDo0g/rss-chan).

> * Added an optional `SESSION_STRING` env variable for RSS feeds. If you know, you know.

> * Added support to `/mirror`, `/qbmirror` & `/leech` (includes all variations: `/zipmirror`, `/zipleech`, etc.) commands to automatically detect an URL when replied to a certain message. This should work for any URL (Magnet, Torrent, Mega & Direct links) you throw at it since it uses regex.

>   * Time taken to process a search query is displayed.

> * Heroku (Dyno) shutdown & reboot functions are added. [Source](https://github.com/breakdowns/slam-mirrorbot/blob/3f60e1975a53c3e2351c0ff43fe95124bfe7e73c/bot/modules/reboot.py).

# Credits

Projects used in the making:

* [rss-chan](https://github.com/hyPnOtICDo0g/rss-chan)
* [mirror-leech-telegram-bot](https://github.com/anasty17/mirror-leech-telegram-bot)

BTW, here's a cute picture of [Hishiro](https://i.imgur.com/QPkgVg6.png).
