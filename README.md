# Diesel Consumption Dashboard

Vite + d3 static dashboard (Jan to 19 Sep 2026, diesel product names only).

```bash
npm install
npm run dev      # local preview
npm run build    # outputs dist/
```

## Deploy to Vercel
Import the folder (or its Git repo) in Vercel. The Vite preset is detected: build command `npm run build`, output directory `dist`. Or run `npx vercel`.

## Updating the numbers
The figures are CSV files in `public/data/` (summary, monthly, groups, vehicles, group_vehicles). Replace them with new exports of the same columns and redeploy.
