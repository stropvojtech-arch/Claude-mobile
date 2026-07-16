# Copenhagen vs Stockholm — Disposable Income for a Marketing Professional

Which Nordic capital leaves a marketing professional with more monthly disposable
income? This analysis compares net salary after tax, minus rent and essential
living costs, for **junior**, **mid-level**, and **senior** marketing roles —
everything converted to **Danish kroner (DKK)**.

- **Full report (tables + charts):** [`reports/copenhagen-vs-stockholm.html`](reports/copenhagen-vs-stockholm.html)
- **Tax year:** 2026 · **FX:** 1 SEK = 0.678 DKK (16 Jul 2026) · **Profile:** single adult, renting alone

## Bottom line

| Level | Copenhagen | Stockholm | Winner | Δ (DKK/mo) |
|---|--:|--:|---|--:|
| Junior | 4,933 kr (22.2% of net) | 6,191 kr (31.0%) | **Stockholm** | +1,258 |
| Mid | 12,909 kr (42.7%) | 13,254 kr (49.0%) | **Stockholm** | +345 |
| Senior | 21,097 kr (54.9%) | 19,691 kr (58.8%) | **Copenhagen** | +1,406 |

*Disposable income = net salary − median rent − essential costs, all in DKK.*

**Verdict:** For the typical (junior–mid) marketing professional, **Stockholm**
leaves more disposable income and a higher share of net pay — driven by far cheaper
rent relative to salary and lighter taxes. **Copenhagen** only wins at **senior**
level, where higher Danish salaries overtake its higher rents. Stockholm keeps a
larger *percentage* of net pay at every level. The verdicts are stable across low,
median, and high rent scenarios (sensitivity analysis in the report).

## How it was built

1. Average gross monthly marketing salaries per seniority (SCB/Unionen for Stockholm;
   Jobindex/Dansk Markedsføring/Business Danmark for Copenhagen).
2. Net salary via 2026 statutory tax rules — DK: AM-bidrag, kommuneskat (København
   23.39%), bund/mellem/topskat, personfradrag, beskæftigelses- & jobfradrag;
   SE: kommunalskatt 30.55%, grundavdrag, jobbskatteavdrag, statlig skatt (calibrated
   to a Stockholm 2026 net-salary calculator).
3. Median one-bedroom rent ~10–15 min from centre by metro, plus essential costs
   (groceries, utilities, internet, mobile, transit).
4. All amounts converted to DKK; disposable income and % of net remaining computed;
   sensitivity run across low/median/high rent.

See the HTML report for full tables, charts, every assumption, and all sources.
