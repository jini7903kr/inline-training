# inline-training — KOS INLINE Academy Pro

Firebase Hosting source for **KOS INLINE Academy Pro** (single-page academy management app).

## Deploy

```bash
firebase deploy --only hosting --project kos-inline-academy
```

Live site: https://kos-inline-academy.web.app/

## Elite super-admin (Classic 2.0)

After **슈퍼관리자** login, the sidebar shows an **엘리트 · 슈퍼관리자** section with shortcuts to:

| Menu | URL |
|------|-----|
| 클래식 2.0 선수 전략 | https://classic-guide.apps.grok.bot/ |
| IFS 룰북 · 심판 | https://ifs-classic20.apps.grok.bot/ |

Center accounts do not see these links.

## Repo layout

- `public/index.html` — full app bundle
- `firebase.json` / `.firebaserc` — Hosting config (`kos-inline-academy`)