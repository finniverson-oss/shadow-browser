# ShadowBrowser launcher

Open [ShadowBrowser](https://finniverson-oss.github.io/shadow-browser/).

This repository hosts the public viewer interface. The connection branch contains runtime.json with the current server address.

The owner starts ShadowBrowser and its Cloudflare tunnel on their PC using Start-ShadowBrowser.cmd. That launcher publishes a new connection address only when it changes. Reload the website to discover the latest address; GitHub caching can briefly delay updates.

The PC and tunnel must stay running. Browser access requires the ShadowBrowser password. No passwords, session tokens, server environment files, or local logs are published here. GitHub hosts the interface, not the Chromium process.

Download [ShadowBrowser.html](https://finniverson-oss.github.io/shadow-browser/ShadowBrowser.html) for a local-file launcher that looks up the same connection address.
