# Module 04 — Options Trading: The Smart Way

**Duration:** Week 8–10 | ~4 hours total  
**Goal:** Understand how options work. Use them to enhance gains without blowing up your account.

---

## WARNING — Read This First

Options are powerful tools that can 10x your money — or wipe out your account in a week. This module teaches conservative, high-probability use of options for a small account. Do not attempt options trading before completing Modules 01 through 03.

---

## 4.1 What Is an Option?

An option is a contract giving you the **right — but not the obligation** — to buy or sell 100 shares of a stock at a specific price (the strike price), before a specific date (the expiration date).

One option contract = 100 shares.

### Call Option
- The right to **buy** shares at the strike price.
- You buy a call when you think the stock is going **up**.
- Your max loss is the premium you paid.
- Your upside is leveraged relative to buying the stock outright.

### Put Option
- The right to **sell** shares at the strike price.
- You buy a put when you think the stock is going **down**, or to protect a position you already own.
- Your max loss is the premium you paid.

---

## 4.2 Key Terms — Learn These Before Anything Else

| Term | Definition |
|------|-----------|
| **Premium** | The price you pay for the option contract. This is your maximum loss when buying options. |
| **Strike Price** | The price at which you can buy (call) or sell (put) the stock. |
| **Expiration Date** | The date the contract expires. After this date, if not exercised, the option is worth zero. |
| **In the Money (ITM)** | The option already has intrinsic value. A $50 call when the stock is at $55 is ITM. |
| **Out of the Money (OTM)** | The option has no intrinsic value yet. A $60 call when the stock is at $55 is OTM. |
| **Theta (Time Decay)** | Options lose value every single day as expiration approaches. Time is your enemy as a buyer. |
| **Delta** | How much the option price changes per $1 move in the stock. A delta of 0.5 means the option gains $0.50 per $1 the stock moves up. |
| **Implied Volatility (IV)** | The market's expectation of future price movement. High IV = expensive options. Buy when IV is low, sell when IV is high. |

---

## 4.3 How an Options Trade Works — Worked Example

Scenario: You believe stock ABC, currently trading at $50, will rise to $60 in the next 60 days.

**Option:** Buy 1 call contract, $52 strike, 60 days to expiry, premium = $2.00/share.

- Cost = $2.00 × 100 shares = $200 total (your max loss)
- Breakeven = $52 + $2.00 = $54.00 (stock must reach this for you to break even at expiry)
- If stock goes to $60: Option worth at least $8.00 × 100 = $800. Profit = $600 on a $200 investment = 300% return.
- If stock stays at $50 or falls: You lose the full $200 premium. Nothing more.

---

## 4.4 Two Strategies for a Small Account

### Strategy 1: Long Calls on Stocks You Believe In

If you have completed the research from Modules 02 and 03 and believe a stock will rise significantly in the next 30–90 days, you can buy a call option instead of the shares.

**Rules for this strategy:**
- Only buy options with **at least 30 days to expiry**. Never buy weekly options with a small account — theta decay will destroy your position before the stock can move.
- Only spend **10–15% of your account on any single options trade** ($75–$112 maximum per trade with a $750 account).
- Buy options that are **slightly out of the money or at the money** — not deep OTM lottery tickets.
- Have a clear exit plan before buying: what is your profit target and what is your stop loss?

### Strategy 2: Covered Calls — Getting Paid to Hold

If you own 100 shares of a stock, you can sell a call option against those shares and collect the premium as income. This is called a covered call.

**How it works:**
- You own 100 shares of XYZ at $7.00 per share = $700 total position.
- You sell a $8.00 call option expiring in 30 days for $0.30/share = $30 premium collected upfront.
- **Outcome A:** Stock stays below $8.00 at expiry. You keep the $30. Repeat next month.
- **Outcome B:** Stock rises above $8.00. Your shares get called away at $8.00. You made $1.00/share × 100 = $100 capital gain + the $30 premium = $130 profit on the position.

The tradeoff: You cap your upside at the strike price. If the stock goes to $15, you still only sell at $8.

**Note:** Covered calls require a Margin account on Questrade even though no margin is actually being used.

---

## 4.5 Setting Up Options on Questrade

1. Navigate to: Account Management → Trading Permissions → Options.
2. Apply for **Level 1** (covered calls and cash-secured puts) and **Level 2** (long puts and calls).
3. Approval typically takes 1–2 business days.
4. Practice first using Questrade's paper trading simulator before risking real money.

---

## 4.6 Options and Fees — The Math Matters

On Questrade: $9.95 + $1.00 per contract per leg.

A single options trade (open + close) = approximately $21.90 in fees for one contract.

If you spend $100 on an option, you need a 22% gain just to break even after fees. This is why:
- You must be high-conviction before entering an options trade.
- Buying and selling options frequently on a small account is a losing strategy.
- Consider holding winning options through expiry or until the gain significantly exceeds fees.

---

## Module 04 Exercise

Before moving to Module 05, complete the following:

- [ ] Apply for options Level 1 and Level 2 permissions on Questrade.
- [ ] Pull up the options chain for one of your researched stocks on Yahoo Finance (Ticker → Options tab).
- [ ] Find a call option 45–60 days to expiry, with a strike approximately 5% above the current price.
- [ ] Record in `progress-tracker.md`: the stock price, the strike, the expiry, the premium, and what the stock would need to do for you to profit.
- [ ] Calculate the total cost including Questrade fees. Is the trade still worth it at that size?
- [ ] Do not buy yet. This is analysis only.

---

## Watch Before Module 05

- YouTube: "Options Trading for Beginners" — Sky View Trading (~30 min)
- YouTube: "Covered Call Strategy Explained" — InTheMoney (~20 min)
- YouTube: "The Greeks Explained Simply" — Options Alpha (~18 min)
- Practice environment: Questrade paper trading (papertrading.questrade.com)
