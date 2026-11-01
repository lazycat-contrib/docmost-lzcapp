# Docmost (LazyCat LPK)

Collaborative wiki and documentation platform.

- Upstream: https://github.com/docmost/docmost
- Image: `docmost/docmost:0.97.0` (mirror mode, digest-matched)
- License: AGPL-3.0 (full text in `content/licenses/LICENSE`)
- Containers: app + PostgreSQL 18 + Redis 8

## Notes
- First-run setup wizard creates the first workspace and admin account; no seeded credential.
- `APP_SECRET` and the database password come from platform stable secrets.
- No mail service configured, so invites/password reset by email are unavailable.
- Not yet verified on a real device.
