# Quotation Maker

Small web app for electrical quotations. Fill in the form on the left, see the A4
quotation update live on the right, then **Save PDF** (or **Print → Save as PDF**).

- Add, remove and reorder items. Amounts and totals are calculated automatically.
- Khmer and English text both work.
- **Save** keeps quotations in the browser (localStorage) so you can open them later.
- **New** starts a fresh quote with the next number and keeps your own details.
- Works on phone too (Edit / Preview tabs).

## Run in Visual Studio Code

Needs Node.js 18+ (https://nodejs.org).

```bash
npm install
npm run dev
```

Open http://localhost:5173

## Deploy on Vercel

1. Put this folder on GitHub (`git init`, commit, push).
2. Go to https://vercel.com/new and import the repository.
3. Vercel detects **Vite** automatically (Build: `npm run build`, Output: `dist`). Click **Deploy**.

Or from the terminal:

```bash
npm i -g vercel
vercel
```

## Notes

- Saved quotations live only in the browser you used. A different phone or computer will not see them.
- If the direct PDF looks wrong on some device, use **Print** and choose "Save as PDF".
