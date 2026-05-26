# COF Calculator — Range × MOA × Target Size

**An interactive tool for designing PRS-style .22 LR matches**, based on real research from 791 targets across 36 NRL22 Courses of Fire (US + South Africa, 2024–2026).

🔫 **[Open the live calculator →](https://YOURUSERNAME.github.io/cof-calculator-22lr/)** *(replace `YOURUSERNAME` with your GitHub username after Pages is enabled)*

---

## What it does

Enter any 2 of these and get the 3rd auto-calculated:
- **Range** (meters)
- **MOA** (angular target size)
- **Target Size** (inches)

The tool then applies **NRL22 research** to give:
- 📊 Database context — how your combo compares to 791 real targets
- 🎯 Stage Type classification (KYL / Positional / Long-Range / Speed)
- 📐 Position recommendations (barricade, tripod, prone…)
- ⏱ Time configurations from real NRL22 stage data
- 🔒 Restriction ideas (difficulty levers)
- 💨 Wind reality check (.22LR vs .308 comparison)
- 💡 Contextual tips

Plus 4 interactive infographics:
1. **Stage Archetype Matrix** — Range × MOA → 4 archetypes
2. **Wind Growth Curve** — .22LR vs .308 wind drift
3. **Size × Distance Regression** — 250 sample targets with regression line
4. **Difficulty Heatmap** — density of NRL22 targets at each Range × MOA combo

---

## How to use

- **Online (recommended):** open the link above on any device (works on iPhone, Android, PC, Mac)
- **Offline:** download `index.html` and open in any modern browser (Chrome, Safari, Edge, Firefox)
- All data is embedded — no internet required after first load

---

## Credit & License

**Created by [Kolawat Runelert](https://www.instagram.com/precisiondynamiclab) · @precisiondynamiclab**

- ✅ **Free to copy, share, print, screenshot, post** for non-commercial / community use
- ✅ **Free to integrate** into your own COF design workflow
- ❌ **Attribution required** — preserve the author name and IG handle in any shared version
- 🚫 **Commercial use** requires permission

If you find it useful, a follow on Instagram is appreciated 🙏

---

## Data sources

Built from analysis of public NRL22 Course of Fire documents (2024–2026):
- US NRL22 monthly COFs (734 targets)
- South Africa NRL22 matchbook COF5–11 + Champs (57 targets)
- Total: **791 targets across 36 unique COFs**

The dataset is included as `combined_target_dataset.csv` in the source folder. Statistical analysis methodology is documented in the accompanying PDF reports.

---

## Tech notes

- Single-file HTML (~310 KB) with everything embedded (CSS, JS, images, dataset summary)
- Pure vanilla JavaScript — no frameworks, no build step
- Works offline once loaded
- iOS Safari compatible (mobile-tested)
- Watermark + attribution integrity check built in

---

## Versions

- **v4** (2026-05-26) — Added hover tooltips, click-to-load, MOA histogram, Stage Archetype Frequency
- **v3** (2026-05-26) — Added watermark, portrait, QR, integrity check, mobile-safe CSS
- **v2** (2026-05-26) — Added 4 interactive SVG infographics
- **v1** (2026-05-26) — Initial release with calculator + NRL22 suggestion engine

---

© 2026 Kolawat Runelert · Released for the Thai PRS .22 community 🇹🇭
