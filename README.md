# DNS configuration

A Pi-hole compatible blocklist containing 27 unique advertising and Unity-related domains from the supplied list, one plain domain per line.

## Add to Pi-hole

Add this URL as a blocking list in Pi-hole's Lists/Adlists page, then update Gravity:

```text
https://raw.githubusercontent.com/progamer3boi/dnsconfig/main/blocklist.txt
```

Roblox, YouTube, Blooket, Clash of Clans, Clash Royale, Stumble Guys, and their related domains are excluded (including Supercell and Kitka Games).

This is a plain domain adlist, not a regex list. Each entry blocks that exact hostname; it does not automatically block every subdomain. The broad Unity CDN entries from the supplied list are retained and may affect Unity content beyond ads.
