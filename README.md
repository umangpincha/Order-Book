# 📋 Order Book App

A mobile-first order entry app with PDF export & WhatsApp sharing.

## 🚀 Deploy to Vercel (3 steps)

### Option A — Vercel CLI (fastest)
```bash
npm i -g vercel
cd orderbook-app
vercel --prod
```
Done! You'll get a live URL like `https://orderbook-xyz.vercel.app`

### Option B — GitHub + Vercel Dashboard
1. Create a GitHub repo and push this folder
2. Go to [vercel.com](https://vercel.com) → New Project → Import your repo
3. Framework: **Other** (static)  
4. Root directory: leave blank  
5. Click **Deploy**

## 📱 Features
- ✅ Mobile-first responsive design
- ✅ All products from ORDER_BOOK_ONLINE.xlsx
- ✅ ± buttons for easy quantity entry (0.5 increments)
- ✅ Auto-saves entries (localStorage)
- ✅ PDF export matching your invoice format
- ✅ WhatsApp share (PDF file on modern phones, text summary as fallback)
- ✅ Section-wise remarks
- ✅ Gross total always visible
- ✅ One-tap clear all

## Files
- `index.html` — entire app (single file, no build step needed)
- `vercel.json` — Vercel deployment config
