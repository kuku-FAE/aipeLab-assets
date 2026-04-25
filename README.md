# aipeLab Assets

Knowledge note assets (frames, diagrams, images) for Notion embedding via jsDelivr CDN.

## Usage

Images are served via jsDelivr CDN:

```
https://cdn.jsdelivr.net/gh/kuku-FAE/aipeLab-assets@main/<path>
```

## Structure

```
frames/
  yt-{video_id}/
    frame_{MM-SS}.jpg          # YouTube key-frame captures
knowledge/
  {topic}/
    {asset}.{ext}              # Diagrams, screenshots, illustrations
```

## Naming

- `MM-SS` (hyphen, not colon) — avoids filename conflicts on all platforms
- `yt-{video_id}` — YouTube video ID prefix for traceability

## Powered by

[`youtube-watcher`](https://github.com/) Claude Code skill — auto-uploads captured key frames and returns jsDelivr URLs for direct Notion embedding.
