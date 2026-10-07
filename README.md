# 📊 DataAgent — Ask Your Data Anything

> 🚧 **Under active development — testing build.** Not everything works yet. You may hit bugs, missing buttons, or rough edges. That's exactly why I'm sharing it: to find what breaks.
>
> Your files never leave your computer. Drop in a spreadsheet, ask in plain English, get charts and answers.

![Free](https://img.shields.io/badge/price-%240%20free-brightgreen)
![Windows](https://img.shields.io/badge/Windows-installer-blue)
![Private](https://img.shields.io/badge/privacy-100%25%20local-orange)
![Offline](https://img.shields.io/badge/offline-capable-purple)
![License](https://img.shields.io/badge/license-AGPL--3.0-lightgrey)

**DataAgent turns boring spreadsheets into clear answers — no Excel formulas, no coding, no monthly fees.**

⚠️ **Honest note:** this v1.0.0 is an early testing release. Core flow (upload → ask → chart → export) works, but some features are incomplete or buggy. Please report whatever you find — broken or confusing counts as useful feedback.

👉 *New here? Start at [Download & try it](#-download--try-it-5-minutes) — you'll have your first chart in 5 minutes.*

---

## ✨ What can you do with it?

| You drop in... | You ask... | You get... |
|---|---|---|
| Shop sales CSV | "Top 5 products this month?" | Bar chart + answer |
| Student marks Excel | "Who improved the most?" | Ranked table + chart |
| Office expenses | "Where is money leaking?" | Category breakdown + PDF report |
| Survey responses | "What do people complain about?" | Summary + key themes |
| Any CSV / Excel / Parquet / JSON | Anything in plain English | Table + chart + explanation |

Plus whenever you need it:

- 📈 **30+ chart types** — bars, lines, pies, maps, funnels, KPIs
- 🖥️ **Dashboards** — drag, resize, save your views
- 📤 **Export anywhere** — Power BI templates (.pbit), PDF reports, PowerPoint slides, Excel workbooks
- 🔮 **Smart help** — forecasts, anomaly alerts ("sales suddenly dropped!"), grouping, what-if checks
- 🔒 **Private by design** — everything runs on your own computer
- 🌙 **Works offline** — internet needed only for the first install

---

## 🧑‍💻 Made by a solo developer

**Independently designed and built by solo developer grg (java22113344).**

No big company, no tracking, no sales calls. Just one builder making data analysis free and private for everyone.

This `v1.0.0` build is shared **for testing** — install it, break it, and report what you find. Your feedback shapes what gets built next.

---

## ⬇️ Download & try it (5 minutes)

### Step 1 — Download

**File:** `DataAgent-Setup.exe`
**Size:** ~508 MB (one-time download, includes everything — no separate installs needed)
**Version:** 1.0.0 — testing release
**Where:** [Releases page](../../releases) → `DataAgent-Setup.exe`

> Direct link after release is published:
> `https://github.com/java22113344/grg-dataagent/releases/download/v1.0.0/DataAgent-Setup.exe`

### Step 2 — Install (Windows 10/11, 64-bit)

1. Double-click `DataAgent-Setup.exe`.
2. Click **Yes** when Windows asks for admin permission.
3. Follow the installer (Start Menu entry + optional desktop icon).
4. If Windows SmartScreen says "Unknown publisher" → click **More info → Run anyway** (normal for a new solo-dev testing build).

Needs about **1.5 GB free space** after install.

### Step 3 — Open it

- **Easiest:** Start Menu → **DataAgent** (desktop window app).
- **Or browser:** open `http://127.0.0.1:8002`.

### Step 4 — Your first answer (2 minutes)

1. Click **Upload** → pick any CSV or Excel file.
2. Click **Ask** → type e.g. `top 5 products by sales`.
3. See your chart → click **Save to dashboard**.
4. Click **Export** → PDF or Power BI template.

🎉 Done! Your file never left your PC.

### Uninstall

Windows Settings → Apps → DataAgent → Uninstall. Your uploaded files live in the app data folder and are removed with it.

---

## 🏪 Everyday uses

**🛍️ Shop owner:** "Which items make me the most money?" — upload daily sales, get top products, slow days, and a printable monthly PDF.

**🎓 Teacher:** "Who needs extra help?" — upload marks, get average, toppers, most-improved, and subject-wise charts for parents' meetings.

**💼 Office manager:** "Where did the budget go?" — upload expenses, get category pie, unusual spikes, and a PowerPoint for the boss.

**🏥 Field worker / NGO:** "What are people saying?" — upload survey CSV, get counts, trends, and a clean summary to share.

**📦 Freelancer:** "Show my client nice reports." — build a dashboard once, export PDF/Excel every month.

---

## 🆚 How DataAgent compares (all 7 rivals)

Full head-to-head against the most popular tools. Prices checked Oct 2026 — vendors change them, so treat as guide.

| Feature | **DataAgent** | Power BI | Tableau | Metabase | Superset | ChatGPT Data Analyst | Julius AI | Obviously AI |
|---|---|---|---|---|---|---|---|---|
| 💰 Price | **$0 free** | $10+/mo per user | $75/mo per user | Free OSS / hosted $85/mo | Free OSS self-host | $20/mo Plus | $45/mo Pro | Custom enterprise |
| 🤖 Ask in plain English | ✅ | Copilot only | ❌ | ❌ | ❌ | ✅ | ✅ | ✅ |
| ⌨️ Writes SQL for you | ✅ | DAX only | ❌ | Limited | ❌ | ✅ | ✅ | ❌ |
| 🖥️ Runs fully on your PC / local AI | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 🔒 Data never leaves device | ✅ | ❌ | ❌ | Self-host only | Self-host only | ❌ | ❌ | ❌ |
| 📊 Interactive dashboards | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | Charts only | Charts only |
| 📈 30+ chart types | ✅ | ✅ | ✅ | 15+ | ✅ | Basic | 10+ | 8+ |
| 📝 File upload (CSV/Excel) | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| 📄 Power BI template export (.pbit) | ✅ | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| 🧾 PDF report export | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ |
| 📽️ PowerPoint export | ✅ | ✅ | Images only | ❌ | ❌ | ✅ | ❌ | ❌ |
| 📗 Excel workbook export | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | CSV only | ✅ |
| 🏠 Self-host / local install | ✅ | Premium only | ✅ | ✅ | ✅ | ❌ | ❌ | ❌ |
| 👥 Logins & roles | ✅ | ✅ | ✅ | Pro only | ✅ | ❌ | ❌ | ❌ |
| 🔑 Company login (SSO) | ✅ | ✅ | ✅ | ❌ | Enterprise | ❌ | ❌ | ❌ |
| 🧾 Activity history (audit) | ✅ | ✅ | ✅ | ❌ | Limited | ❌ | ❌ | ❌ |
| 🔄 Auto clean + load pipelines | ✅ | ✅ | Prep tool | ❌ | ❌ | ❌ | ❌ | ❌ |

### Quick verdicts

- **Choose DataAgent if** you want free + private + offline, with real Power BI export. Only one here that does all three.
- **Choose Power BI if** your whole office already lives in Microsoft and you need big-team governance — but expect $10+/user/month.
- **Choose Tableau if** you do advanced visual design with a large team — but expect ~$75/user/month and no local AI.
- **Choose Metabase / Superset if** you love SQL-first open-source dashboards and can self-host — but don't expect a chat assistant or local AI.
- **Choose ChatGPT / Julius if** you want a quick one-off answer and don't mind uploading your file to their cloud and paying $20–$45/month.
- **Choose Obviously AI if** you want no-code predictions with enterprise support — but expect custom pricing and cloud-only data.

**What only DataAgent does:** local AI chat + data-stays-home + `.pbit` export + full self-host, for $0.

---

## 🔒 Privacy — the simple version

- Your spreadsheets stay on **your** computer. There is no DataAgent cloud copy.
- AI can run **offline** on your PC (built-in local mode). Optional cloud AI keys are off unless you add them.
- No ads, no trackers, no selling data. Uninstall removes everything.
- Logins, roles, and activity history are built in, so shared family/office PCs stay separated.

---

## 💰 Pricing

- **Testing build (this .exe): $0.** Every feature works. No card, no signup wall to try.
- Paid plans (later, on a separate billing site) only raise limits like AI queries — the free local version keeps working.
- Self-hosted = free forever under the open-source license.

---

## ❓ FAQ

**Is my data uploaded anywhere?**
No. Upload means "into the app on your own PC", not the internet.

**Do I need internet?**
Only to download the installer. After that it runs offline. (Optional cloud AI needs internet only if you turn it on.)

**Is it really free?**
Yes for this testing build. No trial timer, no locked charts.

**Windows only?**
This `.exe` is Windows 10/11 64-bit. Mac/Linux users can run the open Docker build (see developer docs).

**Why is the download 508 MB?**
It bundles the app + desktop window + local database engine so you install once and it just works.

**Windows warns about unknown publisher — safe?**
It's unsigned because it's a solo-dev test build, not a big-company release. Code is open-source (AGPL-3.0) so anyone can inspect it.

**Who do I contact?**
Open an [Issue](../../issues) on this repo — it goes straight to grg (java22113344).

---

## 📜 License & credit

Open source under **AGPL-3.0** — free to use, study, and share. See `LICENSE`.

Designed, built, and tested by solo developer **grg (java22113344)**. Thanks for trying the testing build!
