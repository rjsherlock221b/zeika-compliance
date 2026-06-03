# ZEIKA Compliance Hub

Food safety and HACCP management app for ZEIKA Restaurant.
Built for Scotland FSS / UK food hygiene inspection compliance.

## Live App
Once published: **https://YOUR-USERNAME.github.io/zeika-compliance/**

## How to publish on GitHub Pages (free, no expiry)

### Step 1 — Create a GitHub account
Go to **github.com** and sign up (free)

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it: `zeika-compliance`
3. Set to **Public**
4. Tick **Add a README file**
5. Click **Create repository**

### Step 3 — Upload the app file
1. In your new repository, click **Add file** → **Upload files**
2. Drag and drop `zeika-compliance.html`
3. Also upload this `README.md`
4. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Click **Settings** (top of repository)
2. Click **Pages** (left sidebar)
3. Under **Source** → select **Deploy from a branch**
4. Under **Branch** → select **main** → **/ (root)**
5. Click **Save**

### Step 5 — Get your link
Wait 2 minutes, then your app is live at:
**https://YOUR-USERNAME.github.io/zeika-compliance/zeika-compliance.html**

Rename the file to `index.html` when uploading for a cleaner URL:
**https://YOUR-USERNAME.github.io/zeika-compliance/**

---

## Staff PINs
| Name | Role | PIN |
|---|---|---|
| Hakeem | Manager | 1234 |
| Ashik Molath | Manager | 0000 |
| Rahul K. | Staff | 2222 |
| Aman F. | Staff | 3333 |
| Priya S. | Staff | 4444 |

## Features
- Real-time sync via Supabase database
- PIN login for all staff
- HACCP temperature logs (twice daily, all 11 units)
- Toilet cleaning rota (every 2 hours)
- Cooking, reheating, hot holding, cooling logs
- Probe calibration weekly
- Supplier & delivery management
- Auto-fill: fills all pending days automatically at midnight
- Scotland FSS inspection pack PDF
- Weekly, monthly and custom date range reports
- All documents required for Environmental Health inspection
