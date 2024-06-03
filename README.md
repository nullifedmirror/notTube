# nTube (not[You]Tube)

Yet another self-hosted YouTube frontend...

-   Current Release: 1.5.9
-   Next Planned Release: 1.5.10

## Reminder

nTube technically breaks a clause of YouTube's TOS but fully behaves like YouTube's own video player, just without any privacy intrusive crap.

## About

nTube is a self-hosted HTML5 YouTube client that is contained within your internet browser, you can view channels, handle subscriptions, view videos, view playlists, and more!

## Features

-   Supports qualities up to 8K 60fps.
-   Supports downloading videos.
-   Support for various codecs. (VP9/AV1/AC3/DTS)
-   Subtitles support. (both plain and styled)
-   Very experimental DRM support.
-   Livestream support.
-   Livestream chat support.
-   Custom theme support.
-   No advertising.
-   No tracking.
-   Trending and Search support.
-   Channel communities support.
-   Subscriptions.
-   Supports both old and new browsers.
-   Sponsor blocking (capability provided by the SponsorBlock project)
-   User data is confined to your browser.

## Host Requirements

-   Java 8 or newer (up to JRE 16, newer versions are unofficially supported)
-   Internet access
-   At least 512 MB of RAM
-   Single core CPU or better

## Browser Requirements

-   Support for either:
    -   HTML5 video and audio tags
    -   Flash Player (Supported on fallback pages only)
-   HTML 5.0 support
-   ECMAScript 5.0 or newer
-   Media Stream Extensions (MSE) (<b>OPTIONAL</b>)

## Browser support

| Browser           | Unsupported /Untested | Basic Support | Full Support |
| ----------------- | --------------------- | ------------- | ------------ |
| Firefox (20-40)   |                       | X             |              |
| Firefox (52+)     |                       | X             | X            |
| Chrome            |                       | X             | X            |
| Safari (iOS)      | X                     |               |              |
| Safari (iPadOS)   | X                     |               |              |
| Safari (macOS)    |                       | X             |              |
| WebKit (BB10/QNX) |                       | X             |              |
| WebKit (GTK)      |                       | X             |              |

```
Unsupported/Untested: It might work, it might not work. (blame [VENDOR])
Basic Support: Legacy (non-MSE) video playback works.
Full Support: MSE-based video playback works.
```

## Getting Started

1. Download a distribution of nTube.
2. (ideally in a terminal) Launch nTube.
3. nTube should be on port 8080 of localhost.

## Screenshots 📷

![Home Page](screenshots/home_page.png)
![Video Page](screenshots/video_page.png)
![Channel Page](screenshots/channel_page.png)

## Attributions

## License

Licensed under the third version of POSS. (Possibly Open Source Software License)

POSS terms:

Main rules:

-   SOFTWARE_OS: YES
-   SOFTWARE_PAID: NO
-   SOFTWARE_3P_STUFF: YES
-   SOFTWARE_WARRANTY: NO

Subset rules:

-   ENFORCE_TRUE_OSS: YES
-   ALLOW_PAID_FREE: YES
-   ALL_RIGHTS_RESERVED: YES
-   COC_VERSION: 2.0
-   ALL_CHANGES_PUBLIC: NO

## Code of Conduct (CoC)

Uses the second version of the CoC included in the POSS.
