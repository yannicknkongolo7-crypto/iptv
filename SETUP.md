# GitHub Pages Setup

This repository includes HTML stream viewers that can be served via GitHub Pages.

## Enabling GitHub Pages

To enable GitHub Pages for this repository:

1. Go to your repository settings on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment":
   - Source: Select **GitHub Actions**
4. Save the settings

Once enabled, the site will be available at:
```
https://yannicknkongolo7-crypto.github.io/iptv/
```

## Available Stream Viewers

The following HTML viewers are available:

- **Channel Browser** (`channel_browser.html`) - Browse and search through available channels
- **Y-Zone Stream** (`y_zone_stream_enhanced.html`) - Professional multi-stream sports application
- **College Football Simple** (`college_football_simple.html`) - Simple college football stream viewer
- **College Football Multi** (`college_football_multistream.html`) - Multi-stream college football viewer
- **College Football Enhanced** (`college_football_multistream_enhanced.html`) - Enhanced multi-stream viewer

## Manual Deployment

The `.github/workflows/deploy-pages.yml` workflow automatically deploys to GitHub Pages when changes are pushed to the main branch.

You can also manually trigger the deployment:
1. Go to **Actions** tab in your repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click **Run workflow**

## Accessing Your Site

Once deployed, access your stream viewers at:
- Main page: `https://yannicknkongolo7-crypto.github.io/iptv/`
- Channel Browser: `https://yannicknkongolo7-crypto.github.io/iptv/channel_browser.html`
- And so on for each viewer...
