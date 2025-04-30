---
{"dg-publish":true,"permalink":"/digital-garden/stremio/configuring-stremio-addons/","title":"Configuring Torrentio and USA TV Add-ons","tags":["stremio torrentio usa-tv"]}
---


# Configuring Torrentio and USA TV Add-ons

Once you’ve created your Stremio account, the next step is setting up the key add-ons for watching movies, TV shows, and live U.S. television streams.

We'll focus on **Torrentio** (for on-demand movies and shows) and **USA TV** (for live TV).

---

## 🎬 Torrentio Setup (Movies & TV Shows)

Torrentio is a community-created add-on that pulls streaming links from a wide variety of public torrent sources.

> ⚠️ **Disclaimer:**  
> Torrentio doesn’t host any files. It indexes content from across the internet.  
> If you're using a **Debrid service** like Real-Debrid or AllDebrid, you're accessing **cached copies** of torrent files, not downloading or seeding them yourself. This makes streaming faster, safer, and much more reliable.

---

### Step-by-Step Setup

Go to: [https://torrentio.strem.fun/configure](https://torrentio.strem.fun/configure)

Now go through each option in order:

---

### Providers

- Default: `BestTorrentsAll` selected (22 providers).
- Leave this set to all. Torrentio will check all available sources for the best results.

---

### Sorting

- Set to: "By quality then seeders"
- This shows the highest-quality files first, then ranks them by the number of seeders (which often means more reliable playback). Leave this as is.

---

### Priority Foreign Language

- Leave blank unless you specifically want foreign-language releases prioritized.

---

### Exclude Qualities/Resolutions

- To weed out bad or low-quality files, check these:
  - Screener
  - Cam
  - Unknown

This removes most of the blurry or unstable junk.

---

### Max Results Per Quality

- Limits how many results show up per resolution (e.g., 720p, 1080p, 4K).
- Suggested: 3 to 5. This keeps the list manageable.
- Leaving it blank is fine too if you prefer seeing everything.

---

### Video Size Limit

- Leave blank unless you want to filter out very large files.
- Most users should skip this.

---

### Debrid Provider

- Choose either Real-Debrid or AllDebrid.
- This unlocks fast, cached streams and dramatically improves your experience.
- You can change this anytime later.

---

### API Key

- Get your key from your Debrid account:
  - Real-Debrid: [https://real-debrid.com/apitoken](https://real-debrid.com/apitoken)
- Paste it into the field exactly as copied, with no extra spaces.

---

### Debrid Options

There are two optional checkboxes:

- **Don't show download to debrid links**  
  Hides links that are meant for downloading, not streaming. Good for a cleaner interface.

- **Don't show debrid catalog**  
  Hides the section that displays cached torrents from your Debrid account. Optional, but helps simplify things.

If you’re unsure, it’s safe to leave both of these unchecked.

---

### Save and Install

After setting all your preferences:
- Click Save.
- A unique `.json` link will be generated.
- Paste that link into the **Add-on search bar** under Community Add-ons in Stremio and install it.

---

## 📺 USA TV Add-on Setup (Live TV)

USA TV provides access to a large number of publicly available U.S. live TV streams, including local news and network channels.

### How to Install

- Visit: [https://stremio-addons.com/usa-tv.html](https://stremio-addons.com/usa-tv.html)
- Click the "Install (Web)" button to add it to your Stremio account.

> ⚠️ These are public internet streams. Quality and availability vary and depend on third-party sources. The add-on is maintained by one person, so expect occasional downtime.

There are no configuration options needed — just install and start browsing channels.

---

## Final Tips

- Torrentio + a Debrid service is the best combo for reliable streaming.
- Revisit [https://torrentio.strem.fun](https://torrentio.strem.fun) anytime to update your settings.
- If streams aren’t showing up, reinstall the add-on using a fresh link.
- This setup works great, but don’t expect 100% uptime or full cable replacement. There’s no official support, and pieces can break temporarily.

---

Now you're ready to stream movies, shows, and live TV — directly from inside Stremio.