
1. In Options Trading

    Bull Spread: Designed to profit when the underlying asset goes up (e.g., Bull Call Spread or Bull Put Spread). You buy an option at a lower strike and sell an option at a higher strike.

    Bear Spread (The Opposite): Designed to profit when the underlying asset goes down.

        Bear Put Spread: You buy a put option at a higher strike and sell a put option at a lower strike (paying a net debit). You profit if the stock price falls.

        Bear Call Spread: You sell a call option at a lower strike and buy a call option at a higher strike (receiving a net credit). You profit if the stock price stays flat or falls.




With **INTC currently trading at $100**, here is the complete expiration breakdown for the **Bear Call Spread** setup from our previous turn (**Sell 1 $105 Call for $3.00 credit / Buy 1 $110 Call for $1.00 debit = $2.00 net credit**, or **$200 per contract**).

---

### Expiration Payoff Breakdown Across All Price Scenarios

| INTC Price at Expiration | Short $105 Call Value | Long $110 Call Value | Net Spread Intrinsic Value | Net Profit / Loss (per share) | Net Profit / Loss (1 Contract) | Outcome |
| --- | --- | --- | --- | --- | --- | --- |
| **$90.00** (Drops 10%) | $0.00 (Expires worthless) | $0.00 (Expires worthless) | $0.00 | **+$2.00** | **+$200** | **Max Profit** |
| **$100.00** (Stays flat) | $0.00 (Expires worthless) | $0.00 (Expires worthless) | $0.00 | **+$2.00** | **+$200** | **Max Profit** |
| **$105.00** (At short strike) | $0.00 (Expires worthless) | $0.00 (Expires worthless) | $0.00 | **+$2.00** | **+$200** | **Max Profit** |
| **$106.00** (Slightly above) | -$1.00 | $0.00 | -$1.00 | **+$1.00** | **+$100** | **Partial Profit** |
| **$107.00** (Break-even) | -$2.00 | $0.00 | -$2.00 | **$0.00** | **$0** | **Break-Even** |
| **$108.50** (Mid-spread) | -$3.50 | $0.00 | -$3.50 | **-$1.50** | **-$150** | **Partial Loss** |
| **$110.00** (At long strike) | -$5.00 | $0.00 | -$5.00 | **-$3.00** | **-$300** | **Max Loss** |
| **$125.00** (Rallies 25%) | -$20.00 | +$15.00 | -$5.00 | **-$3.00** | **-$300** | **Max Loss (Capped)** |

---

### The 4 Core Scenarios Explained

#### 1. INTC Drops, Stays Flat, or Rises Slightly (At or Below $105.00)

* **What happens:** Both the $105 call and $110 call expire completely worthless because INTC is below both strike prices.
* **Result:** You keep the entire **$2.00/share ($200)** credit received upfront. This is your **Maximum Profit**, and it gives you a $5.00 upside cushion from the current $100 price before you lose a single cent of profit.

#### 2. INTC Closes Between $105.00 and $107.00 (Profitable Buffer Zone)

* **What happens:** Your short $105 call is in-the-money (ITM), while your $110 call expires worthless. Your broker automatically debits the intrinsic value of the $105 call at expiration (or you buy it back before the bell).
* **Result:** Because you collected $2.00 upfront, you still walk away with a **net profit** anywhere below **$107.00**. For example, at $106.00, the $105 call costs $1.00 to settle, leaving you with **+$1.00 ($100)** profit.


Think of this zone like having a **$2.00 head start** in a race.

Even though the stock went slightly above your **$105** limit, you still walk away with a profit because of the money you collected upfront.

Here is how it works in plain English, using **$106** as an example:

1. **You started with +$2.00 in your pocket:** When you opened the trade, you collected $2.00 per share ($200 total). That money is yours to keep right away.
2. **The $110 protection does nothing:** Since INTC finished at $106, your $110 safety net wasn't needed and simply expires.
3. **You have to pay back the extra $1.00 above $105:** Because you promised to sell INTC at $105, and it is now worth $106, you owe the **$1.00 difference** per share ($100 total) to close out that promise.
4. **You keep the leftover $1.00:** You take the $2.00 you collected at the start, pay the $1.00 you owe at the finish, and pocket the remaining **+$1.00 per share ($100 profit)**.

**In short:** Your $2.00 upfront payment acts like a cushion. As long as INTC finishes below **$107** ($105 + your $2.00 cushion), you pay back less than what you collected upfront, so you still make money.

#### 3. INTC Closes Between $107.01 and $109.99 (Partial Loss & Pin Risk Zone)

* **What happens:** The cost to settle the short $105 call exceeds your initial $2.00 credit, while the $110 call still expires worthless.
* **Result:** You incur a **partial loss** between $0.01 and $2.99 per share.
* **Important Warning (Pin Risk):** If INTC is hovering right between $105 and $110 on expiration afternoon, **close the spread before the market closes**. If you let it expire in this zone, you will be assigned short 100 shares of INTC at $105 over the weekend without the $110 call protecting you on Monday morning.

#### 4. INTC Rallies Strongly (At or Above $110.00)

* **What happens:** Both calls are in-the-money. You are obligated to sell shares at $105, and your long $110 call exercises to buy shares at $110—locking in a $5.00/share gross spread difference.
* **Result:** After subtracting your $2.00 upfront credit, your loss is strictly capped at **-$3.00/share (-$300)**. Even if INTC surges to $150 or $200, your loss never exceeds $300.

---
