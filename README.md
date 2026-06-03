# Spider Peers — release binaries

Free CDN hosting for the [Spider Peers](https://peers.spider.cloud) agent
binaries (macOS universal + Apple Silicon `.dmg`, Android/TV `.apk`), published
as GitHub Releases under the rolling [`latest`](../../releases/latest) tag.

Downloads on peers.spider.cloud try **GitHub first** (free egress via GitHub's
CDN) and fall back to the `api.spider.cloud` proxy, so binary bandwidth doesn't
hit our servers.

Direct URLs:
- `https://github.com/spider-rs/spider-peers-dist/releases/download/latest/Spider-Peers-0.1.0-universal.dmg`
- `https://github.com/spider-rs/spider-peers-dist/releases/download/latest/Spider-Peers-0.1.0-arm64.dmg`
- `https://github.com/spider-rs/spider-peers-dist/releases/download/latest/Spider-Peers-0.1.0.apk`

Binaries are signed (Developer ID for macOS; release-keystore for Android).
