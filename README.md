# Apparel Capacity Planning Tools

Two Excel-based tools built to apply data analysis and statistics skills to real 
production planning and industrial engineering problems in apparel manufacturing.

Built with **sample/simulated data** for demonstration purposes — not based on any 
real company's production data.

---

## 1. Apparel Line Loading & Capacity Planning Tool

A formula-driven capacity planning model that compares **available line capacity** 
against **required capacity** from an order book, across multiple production lines 
and weeks.

**What it does:**
- Calculates available capacity per line (operators × hours × efficiency %)
- Calculates required capacity per order (quantity × SMV)
- Flags overloaded / underloaded weeks automatically
- Live dashboard showing load % by line, with conditional formatting

**Tools used:** Excel, INDEX/MATCH, SUMIFS, conditional formatting, charts

📄 File: `Apparel_Capacity_Planning_Tool.xlsx`

---

## 2. Line Balancing & SMV Breakdown Analysis

An operation-level line balancing model for a basic garment style, showing how 
rebalancing work across stations reduces the bottleneck and improves efficiency.

**What it does:**
- Breaks a garment down into 12 sewing operations with individual SMVs
- Assigns operations to 5 workstations (before layout)
- Identifies the bottleneck station and calculates Balance Efficiency %
- Rebalances the same operations (after layout) to reduce the bottleneck

**Result:** Balance Efficiency improved from **77.3% → 91.9%** by redistributing 
operations across stations — no added headcount or machines.

**Tools used:** Excel, SUMIF, MAX, formula-driven modeling

📄 File: `Apparel_Line_Balancing_Tool.xlsx`

---

## About

Built by Isuri Dharmasena to apply an Applied Statistics / data analysis background 
to apparel-sector production planning and industrial engineering roles.

🔗 [LinkedIn](https://www.linkedin.com/in/isuri-dharmasena-7137791ba/)
