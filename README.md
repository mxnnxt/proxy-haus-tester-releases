<div align="center">

<img src="assets/icon.png" width="112" alt="PROXY HAUS Tester">

# PROXY HAUS Tester

**Fast, accurate proxy testing for ISP and residential lists. Test thousands at once, right from your own computer.**

[![Latest release](https://img.shields.io/github/v/release/mxnnxt/proxy-haus-tester-releases?label=latest&color=ff5b1f&style=flat-square)](https://github.com/mxnnxt/proxy-haus-tester-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/mxnnxt/proxy-haus-tester-releases/total?color=2b2b31&style=flat-square)](https://github.com/mxnnxt/proxy-haus-tester-releases/releases)
![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-2b2b31?style=flat-square)
![macOS](https://img.shields.io/badge/macOS-11%2B-2b2b31?style=flat-square)

[Download](#download) · [Features](#features) · [Getting started](#getting-started) · [Speed grades](#speed-grades) · [FAQ](#faq)

<br>

<img src="assets/banner.jpg" alt="PROXY HAUS Tester: paste a list, pick a site, watch results land" width="100%">

</div>

<br>

## Download

<div align="center">

<a href="https://github.com/mxnnxt/proxy-haus-tester-releases/releases/latest/download/PROXY-HAUS-Tester-Setup.exe"><img src="assets/download-windows.svg" alt="Download for Windows" height="64"></a>
&nbsp;&nbsp;
<a href="https://github.com/mxnnxt/proxy-haus-tester-releases/releases/latest/download/PROXY-HAUS-Tester-mac.dmg"><img src="assets/download-mac.svg" alt="Download for macOS" height="64"></a>

<sub>Always the newest version · [All releases](https://github.com/mxnnxt/proxy-haus-tester-releases/releases)</sub>

</div>

<br>

## Features

- **Real ms, from your machine.** Every test runs locally through each proxy to the site you pick, so the numbers match what your tasks see.
- **Built for big lists.** Thousands of proxies per run, with results animating in as they land. Gateway lists are paced so the gateway doesn't inflate your numbers.
- **Test against the sites you run.** Google, Shopify (any store domain), Walmart, Pokémon Center, Target, Amazon, Best Buy, GameStop, or add your own.
- **ISP or resi, detected automatically.** Speed grades adjust to the list type.
- **Location and ISP for every proxy.** City, region, ISP, ASN, and whether the IP is ISP, mobile or datacenter.
- **Export by speed.** Copy or save only the Great and Good proxies, fastest first, in the format your bot wants.
- **Lists and history.** Save lists, retest in one click, and copy the fast ones from any past test.

<div align="center">
<img src="assets/export.jpg" alt="Export by speed" width="49%">
<img src="assets/history.jpg" alt="Test history" width="49%">
</div>

## Getting started

1. **Install.** Download above and run the installer.
2. **Paste your proxies.** Any common format works: `ip:port:user:pass`, `user:pass@host:port`, `http://…`, `socks5://…`
3. **Pick a site** from the dropdown next to your list.
4. **Hit Test.** Then filter by Great / Good / OK and hit **Export**.

## Speed grades

| List type | Great | Good | OK |
|---|---|---|---|
| **ISP** (static IPs) | under 100 ms | 100–300 ms | 300 ms+ |
| **Resi** (gateways / rotating) | under 500 ms | 500–1000 ms | 1000 ms+ |

The ms column can show three measurements:

- **Warm** (default): a request on an already-open connection, which is what a running task feels.
- **Tunnel**: network only, through the proxy to the site.
- **Cold**: a brand-new connection, start to finish.

## FAQ

<details>
<summary><b>Windows says "Windows protected your PC"</b></summary>
<br>
Click <b>More info → Run anyway</b>. This shows for new apps until enough people have downloaded them.
</details>

<details>
<summary><b>macOS says the app can't be opened</b></summary>
<br>
Right-click the app → <b>Open</b> → <b>Open</b>. Or go to <b>System Settings → Privacy &amp; Security</b> and click <b>Open Anyway</b>.
</details>

<details>
<summary><b>Where are my lists stored?</b></summary>
<br>
On your computer only. Nothing is uploaded. Location data comes from ipwhois.io, which only receives the proxy IP address.
</details>

<details>
<summary><b>How do I update?</b></summary>
<br>
Download again from this page and run the installer. Your lists and history are kept.
</details>

<br>

<div align="center">

**Need faster, cleaner proxies?** → [proxy-haus.com](https://proxy-haus.com)

<sub>© PROXY HAUS. All rights reserved. This repository only hosts installers.</sub>

</div>
