# Job Match Alert

求人新着・条件一致通知

## Web

- GitHub Pages: https://syunnjack.github.io/job-match-alert/
- Build command: `npm run build`
- Build output: `dist`

`main` ブランチへの反映後、GitHub Actions が lint、build、GitHub Pages へのデプロイを実行します。

## Domain candidates

Future custom domain: `jobmatchalert.jp`

Other candidates:

- `jobping.jp`
- `kyujinalert.jp`
- `workmatch.jp`

## Concept

条件一致求人、新着、締切、面接枠を通知し、採用成果報酬と掲載課金へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 採用成果報酬
- 掲載課金
- 面接予約
- スカウト課金
- 広告

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
