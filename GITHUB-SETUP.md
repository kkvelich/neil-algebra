# GitHub Pages Setup — 5-Minute Walkthrough

**Goal:** turn this folder into a public website at
`https://[your-username].github.io/neil-algebra/` — works on Mac, iPad, iPhone,
anywhere. URL stays the same forever even when we update the files.

## What you need

- GitHub account (you have this ✅)
- 5 minutes
- A modern browser (Chrome, Safari, Firefox — any)

## Step 1 — Create a new repository (1 min)

1. Go to **https://github.com/new** (you must be logged in)
2. Repository name: `neil-algebra` (or anything you like — but lowercase, no spaces)
3. Description: `Neil's Algebra 1 practice materials`
4. Visibility: **Public** (required for free GitHub Pages — see "Privacy notes" below)
5. ✅ Check **Add a README file**
6. Click **Create repository**

## Step 2 — Upload the files (2 min)

1. On the new repo page, click **Add file → Upload files**
2. In Finder, open the `Neil Algebra1/github-site/` folder
3. **Select ALL files inside** (Cmd+A) and drag them onto the GitHub page
4. Wait for the upload progress bar to finish (you'll see all filenames listed)
5. Scroll to the bottom: commit message can be `Initial upload`
6. Click **Commit changes**

## Step 3 — Enable GitHub Pages (1 min)

1. In the repo, click the **Settings** tab (top right of the repo page)
2. In the left sidebar, click **Pages**
3. Under "Build and deployment" → "Source": select **Deploy from a branch**
4. Under "Branch": select **main** and **/ (root)**, then click **Save**
5. Wait ~30 seconds. Refresh the page. You'll see a green box: "Your site is live at..."
6. Copy the URL — that's your public link.

## Step 4 — Test it (30 sec)

1. Open the URL on your iPhone or iPad in Safari
2. The hub page should load — colored cards, exam countdown, everything
3. Tap **Math Quest App** to make sure it loads
4. Tap Safari's Share button → **Add to Home Screen** → Add
5. Now Neil has a home-screen icon that opens the app instantly

## Step 5 — Share with the tutor

Send the URL via iMessage or email:
> Hi [tutor name], here's everything for Neil: https://[your-username].github.io/neil-algebra/tutor-briefing.html

She can open in any browser, on any device. The Math Packet and embedded study
guides are all linked from the briefing.

---

## To update the app later

When I rebuild the Math Quest app (more problems, bug fixes, etc.), you just:

1. Go to your repo on github.com
2. Click on `math-quest.html`
3. Click the pencil icon (edit) — or click "Delete this file" and re-upload the new one
4. For multiple file updates: click **Add file → Upload files** and drag the new versions

GitHub Pages auto-deploys within 30 seconds. The URL stays the same.

---

## Privacy notes

- **Anyone with the URL can access the site.** The repo is public, but the URL is
  long and random-ish — no one is going to guess it. This is the same level of
  privacy as a Google Drive "anyone with the link" share.
- **No personal info should be in the repo.** I've kept Neil's school account
  number, etc., out of the files. The teacher PDFs are the teacher's own work
  product — you have the right to keep your own copies. Don't share the public
  URL anywhere indexed (don't post on social media, don't include in a Google
  search-indexed forum).
- **Want truly private?** Upgrade to GitHub Pro ($4/mo) for private Pages, or
  use a password-protected option like Netlify with auth. For Neil's use case,
  public-with-random-URL is fine.

## Troubleshooting

**Site shows 404:**
- Wait 1–2 minutes after enabling Pages — first build takes a moment
- Make sure you selected branch `main` (not `gh-pages`) and `/` (root)

**File doesn't load (HTML or PDF):**
- Check the URL has the exact filename (case matters: `math-quest.html` ≠ `Math-Quest.html`)
- The Settings → Pages section will show any build errors

**Math Quest app loads but Neil's progress doesn't save:**
- That's expected — localStorage is per-device. Pick one device (the iPad) as
  the practice device. Progress saves there only.
