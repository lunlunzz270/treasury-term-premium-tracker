# Treasury Term Premium & Bond Duration Monitor

A financial research monitor designed to track the multi-year dynamics between **10-Year Treasury Bond Duration**, the **Federal Reserve Bank of New York ACM 10-Year Term Premium**, benchmark **10-Year Treasury Yields**, and their empirical transmission to the **U.S. Equity Market (S&P 500 Index)**.

---

## 🚀 Live Demo & Public GitHub Pages URL

* **Live URL**: `https://lunlunzz270.github.io/treasury-term-premium-tracker/`

---

## 📊 Core Empirical Findings & Macroeconomic Transmission

* **Identified Event Window**: July 14, 2023 to October 19, 2023 (Equity market pullback: July 31, 2023 to October 27, 2023).
* **Key Statistics**:
  * **10-Year ACM Term Premium Surge**: Advanced from **-0.52% (-52 bps)** to **+0.33% (+33 bps)**, surging by **+85 basis points**.
  * **10-Year Benchmark Yield**: Rose from **3.81% to 4.98% (+117 bps)**. The expansion in term premium alone accounted for **72.6%** of the total surge in benchmark yields.
  * **10-Year Bond Duration**: Contracted from **8.24 years down to 7.72 years** (-0.52 years).
* **Observable Cross-Market Impact**: **U.S. Equity Market (S&P 500 Index / SPX)**.
  * Over this exact window, the S&P 500 underwent a technical correction, retreating from **4,588.96 down to 4,117.37 (-10.28%)**.
* **Economic Mechanism**: The term premium represents the compensation demanded by investors for bearing duration risk (amplified by massive Treasury coupon supply announcements in Q3 2023). Because long-term risk-free rates serve as the discount denominator in equity valuation models, this +85 bps spike in term premium directly elevated equity discount rates, compressing the S&P 500 forward P/E multiple from **20.4x down to 18.2x**.

---

## 🛠️ Deploy to GitHub Pages (1-Minute Guide)

### Step 1: Create a New GitHub Repository
1. Log in to [GitHub](https://github.com/).
2. Click **New Repository** (or visit https://github.com/new).
3. Name it: `treasury-term-premium-tracker`.
4. Set it to **Public**. Click **Create repository**.

### Step 2: Push Local Files to GitHub
Run in your terminal:
```bash
cd "/Users/zilun/fintech/Fintech_534/Homework/hw3/sheet1_website"
git init
git add .
git commit -m "feat: Treasury Term Premium & Duration Tracker"
git branch -M main
git remote add origin https://github.com/lunlunzz270/treasury-term-premium-tracker.git
git push -u origin main
```

### Step 3: Turn on GitHub Pages
1. Go to repository **Settings** > **Pages**.
2. Under **Build and deployment** > **Branch**, select `main` and `/ (root)`.
3. Click **Save**. Within 30 seconds, your site will be live at:  
   `https://lunlunzz270.github.io/treasury-term-premium-tracker/`

---

## 💻 Local Preview
To preview locally:
```bash
open "/Users/zilun/fintech/Fintech_534/Homework/hw3/sheet1_website/index.html"
```
