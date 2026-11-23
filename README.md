# Classical Optimisation Models

Interactive teaching pages for the Business Analytics module: employee scheduling, blending, transportation, logistics networks and aggregate planning.

Open `index.html` to start. Every page works offline: the maths display library is included in `assets/`.

## Publish with GitHub Pages

1. Sign in at github.com and click **New repository**. Give it a name such as `optimisation-models`, set it to **Public**, and create it.
2. On the new repository page, click **uploading an existing file**. Drag in everything from this folder, including the `assets` folder and the `.nojekyll` file, then click **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, choose **Deploy from a branch**, select **main** and **/ (root)**, and click **Save**.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/optimisation-models/`.

To update a page later, upload the new file with the same name; the site refreshes within a couple of minutes and the link stays the same.

## Add to Blackboard

**Recommended:** add each page (or the landing page) as a web link set to open in a new window.

**Embedding:** paste one line into an HTML block, using a fixed height:

```html
<iframe src="https://YOUR-USERNAME.github.io/optimisation-models/redbrand.html" width="100%" height="900" style="border:0" title="RedBrand logistics model"></iframe>
```

Inside an embedded frame, Presenter mode works best if students open the page in its own tab.

## Files

| File | Model |
|---|---|
| `index.html` | Landing page |
| `scheduling.html` | 14.1 Employee scheduling (Briggs) |
| `blending.html` | 14.2 Blending (Chandler Oil) |
| `transportation.html` | 14.3 Transportation (Grand Prix) |
| `redbrand.html` | 14.4 Logistics networks (RedBrand) |
| `aggregate.html` | 14.5 Aggregate planning (SureStep) |
| `assets/tex-svg.js` | MathJax 3.2.2 (Apache 2.0 licence), used to display the maths |
