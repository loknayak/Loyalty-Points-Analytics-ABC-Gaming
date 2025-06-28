# 🎮 ABC Gaming – Loyalty Points Analysis

This project analyzes player behavior on a real-money gaming platform by evaluating the company’s loyalty points model and fairness in bonus distribution.

---

## 📌 Project Objectives

- ✅ Calculate player-wise **loyalty points** using deposit, withdrawal, and gameplay data.
- ✅ Assign loyalty points to **time-based slots** (S1: before noon, S2: after).
- ✅ Generate a **monthly leaderboard** based on user performance.
- ✅ Fairly distribute bonus to **top 50 players**.
- ✅ Evaluate the **fairness and efficiency** of the current loyalty model.

---

## 📈 Key Features

- **Function-based modular analysis** using pandas.
- **KPI generation** – Avg deposit, withdrawal, and games per user.
- **Slot-based filtering** and comparison between time windows.
- Clear ranking and **bonus allocation logic** tied to loyalty.

---

## 🧮 Loyalty Formula

Loyalty points calculated using:
```python
Loyalty = 0.01 * Deposit_Amount 
        + 0.005 * Withdrawal_Amount 
        + 0.001 * (Deposit_Count - Withdrawal_Count)
        + 2.0 * Games_Played
