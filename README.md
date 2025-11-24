# Student Investment Risk Dashboard 🎓📈

> **If you had just $100 to invest as a student, where would you put it – and how risky would that choice be?**

This project is an interactive Tableau story built for **IST 737: Visual Analytics Dashboard** at Syracuse University.  
It is designed for **first-time student investors** who feel overwhelmed by stocks, risk, and market jargon – and want a simple, visual way to explore it all.

---

## 🎯 What This Project Is About

Most students know they *should* invest, but:

- Markets feel scary (crashes, recessions, “volatility” 🤯)  
- Risk is hard to understand in numbers  
- Macro indicators (like VIX, CPI, TED Spread) sound like buzzwords  

This dashboard tells a **step-by-step story**:

1. Why investing early matters  
2. How markets behave in crashes and recoveries  
3. What “risk” and “volatility” actually look like  
4. What hidden market forces are doing in the background  
5. How different stocks compare  
6. How current conditions look on a “risk scorecard.”  
7. How a **$100 student portfolio** changes with risk appetite  

By the end, a student can say:  
> *“I understand what I’m investing in, how risky it is, and why the market feels the way it does.”*

---

## 🗂 Data & Sources

We combine student-specific portfolio data with real market & macro data:

- **Stock price & returns** – Yahoo Finance  
- **Volatility (VIX)** – market “fear index”  
- **CPI** – inflation trends over time  
- **TED Spread** – liquidity & credit stress in financial markets  
- **Credit Spread (BAML)** – corporate bond risk signal  
- **Student portfolio & budget data** – simulated student allocations and investment choices  

In the packaged workbook (`.twbx`), these live as:

- `Enriched_Multi_Ticker_Dataset.xlsx`  
- `macro_indicators.xlsx`  
- `vix_data.xlsx`  
- `return_projection.xlsx`  
- Hyper extracts:
  - `Sheet1 (student_portfolio_allocation).hyper`
  - `Sheet1 (student_budget).hyper`

---

## 📖 Story Flow – Slide by Slide

The Tableau workbook is built as a **story** with multiple dashboards:

### 1️⃣ Slide 1 – *Why Should a Student Invest?*

**Goal:** Show that *time in the market* matters more than timing the market.

What you see:
- A simple compounding/growth comparison.
- How starting at 20 vs 30 vs 40 can drastically change outcomes.

How to interact:
- Change assumed return rate (if parameterized).
- Compare growth curves to see how early investing pays off.

**Key takeaway:**  
> Waiting to invest is expensive. Even small amounts grow meaningfully over time.

---

### 2️⃣ Slide 2 – *Market Crashes & Volatility*

**Goal:** Normalize fear around crashes by showing **crash → recovery cycles**.

What you see:
- Timeline of major crashes and recoveries.
- How the market has bounced back after historic drawdowns.

How to interact:
- Hover over crash periods for annotations.
- Focus on specific time windows to see recovery length.

**Key takeaway:**  
> Crashes are part of the game, but the long-term trend still favors patient investors.

---

### 3️⃣ Slide 3 – *Volatility = Risk (AAPL vs TSLA & others)*

**Goal:** Turn abstract “risk” into something visual and intuitive.

What you see:
- Charts like:
  - **Return vs volatility**
  - **Average beta by company**
  - Comparisons like *Apple vs Tesla*

How to interact:
- Highlight individual tickers.
- Compare stable vs high-volatility stocks.

Try this:
- Select a high-volatility stock (like TSLA) and a lower-volatility one (like AAPL).
- Watch how much more the “risky” stock moves for the same market move.

**Key takeaway:**  
> Higher volatility = wilder swings = more emotional stress and potential reward.

---

### 4️⃣ Slide 4 – *The Hidden Forces: Macro Indicators*

**Goal:** Show that markets are not random – they respond to deeper forces.

What you see:
- Visualizations for:
  - **VIX over time**
  - **CPI vs Treasury**
  - **TED Spread**
  - **Credit Spread**

How to interact:
- Hover over spikes in VIX or TED Spread.
- See where macro stress lines up with market turbulence.

Try this:
- Find periods where VIX spikes and TED/credit spreads widen.
- Relate those to known crises (e.g., 2008, COVID crash).

**Key takeaway:**  
> Macro indicators can act like “weather forecasts” for financial markets.

---

### 5️⃣ Slide 5 – *Stock Comparison (Risk vs Return)*

**Goal:** Help students distinguish **aggressive vs conservative** choices.

What you see:
- Scatter plots or charts like:
  - **Return by ticker**
  - **Volatility by ticker**
  - **Volatility heatmaps**

How to interact:
- Click different tickers to compare.
- Filter by sector or risk band if filters are available.

Try this:
- Identify:
  - 1–2 relatively stable candidates
  - 1–2 very risky candidates  
- Ask: *Would I personally be comfortable holding this during a crash?*

**Key takeaway:**  
> Not all stocks are equal; some are built for stability, others for thrill-seekers.

---

### 6️⃣ Slide 6 – *Market Risk Scorecard*

**Goal:** Present a quick **“How risky does the world look right now?”** panel.

What you see:
- A dashboard with KPIs like:
  - Latest **VIX level**
  - **CPI trend**
  - **TED Spread**
  - **Credit Spread**

How to interact:
- Hover for historical context.
- Use parameters or filters (if present) to adjust the view.

**Key takeaway:**  
> Students can check a few simple metrics before investing instead of guessing.

---

### 7️⃣ Slide 7 – *$100 Student Portfolio Simulator*

**Goal:** Make it real and personal: *“If I invest $100, what does that look like?”*

What you see:
- A simulated **student portfolio**:
  - Low-risk allocation
  - Medium-risk allocation
  - High-risk allocation
- Distribution of funds across stocks/categories.
- Possibly expected return vs risk for each profile.

How to interact:
- Select different **risk appetite** levels.
- See how allocations update.
- Compare:
  - % in stable vs aggressive assets
  - Projected growth vs volatility

Try this:
- Start with a **low-risk** student.
- Then switch to **high-risk** and see how the mix changes.

**Key takeaway:**  
> Students learn to align their portfolio with their true comfort level, not just “chasing returns.”

---

## 🧭 How to Use This Project

1. **Download the workbook**  
   - `Student-Investment-Risk-Dashboard_TableauPublic.twbx`

2. **Open in Tableau**  
   - Use Tableau Desktop or Tableau Public (desktop app).

3. **Click through the story**  
   - Follow the slides from **Slide 1** to **Slide 7**.
   - Treat it like a guided investing lesson.

4. **Experiment & explore**  
   - Change filters, hover over marks, switch risk profiles.
   - Ask yourself: *“Would I invest like this?”* and *“What am I comfortable losing?”*

---

## 🧩 What This Project Demonstrates

From a **data & analytics** perspective:

- Data blending: equities, volatility, macro indicators, student-level portfolios  
- Visual storytelling: slides built as **dashboards in sequence**  
- Risk communication: turning complex financial concepts into approachable visuals  

From a **student investor** perspective:

- Why starting early matters
- How to read basic market signals
- How to think in terms of *risk appetite*, not just “what stock is hot”

---

If you’re a recruiter, instructor, or fellow student:
- This project shows not just **visualization skills**, but also the ability to **educate non-technical users** about a complex, emotional topic: *money and risk*.
