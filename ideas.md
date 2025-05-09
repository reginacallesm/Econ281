# Econ 281: Research Ideas  
**Regina Calles**

---

## Idea 1

### Research Question  
**Does the strategic overstatement of state spending to draw down additional federal transfers alter the local, cross-sectional government-spending multiplier?**

### Motivation  
A couple of days ago, I read this in the NY Times:  
**[G.O.P. Targets a Medicaid Loophole Used by 49 States to Grab Federal Money](https://www.nytimes.com/2025/05/06/upshot/medicaid-hospitals-republicans-cuts.html)**

The article explains how nearly every U.S. state uses a Medicaid financing tactic known as a **provider tax**, where hospitals are taxed by the state and then reimbursed at higher rates for treating Medicaid patients.

![Diagram of Provider Tax Loophole](Screenshot%202025-05-08%20at%2011.46.17%20PM.png)

This setup allows states to inflate reported Medicaid spending, which boosts the amount of federal matching funds they receive—without increasing actual state fiscal effort. The federal government bases its match on gross spending, not net state contributions, so states effectively extract more federal money by looping funds through providers.

According to the article, provider taxes now underwrite approximately one-third of federal Medicaid transfers in several states. Since states can increase federal contributions without raising real state expenditures, estimates of regional fiscal multipliers—assuming local effort behind observed spending—may be upwardly biased.

### How to Answer  
I thought that this could be an interesting application of **Nakamura and Steinsson’s framework**. They distinguish between federally and locally financed spending, showing that the multiplier is only modestly affected by the source of funding—particularly under complete markets.

The Medicaid provider-tax mechanism mimics a shift from state-financed to federally financed spending by using recycled provider taxes to unlock higher federal matches, without increasing real state fiscal effort.

However, to accurately model this case, one would need to go beyond simply changing the funding source and explicitly capture the strategic manipulation of the financing structure. That is, the spending increase is largely accounting-based, not cash-based.

Incorporating this type of substitution—where gross reported spending rises but net fiscal effort stays flat—could help reveal how the composition of financing affects local output responses, not just its origin. I’m not yet sure how this could be formally included.

---

## Idea 2

### Research Question  
**How does the size of the informal sector affect the estimated local fiscal multiplier?**

### Motivation  
In the papers that we read for class, there is a common assumption that people pay taxes. But in many developing countries, a large share of employment and output is informal—untaxed, and often outside the reach of state policy. This raises a key concern: does public spending generate the same economic response when much of the local economy is disconnected from the formal fiscal channel? If informality weakens tax feedback, dampens labor mobility, or reduces spending visibility, then traditional estimates may misrepresent the true impact of fiscal stimulus in these settings.

### How to Do It  
Leverage **locality variation** in informality—measured from labor‑force surveys in Mexico—and pair it with plausibly exogenous fiscal shocks to estimate heterogeneous multipliers.

A potential source of exogenous spending is Mexico's *cash transfers to adults 65+ (since 2019)*: eligibility is age‑based and thus potentially orthogonal to local informality rates.

Combine share of 65+ population per locality with municipality‑level informality shares to estimate the multiplier following the cross‑sectional approach of Nakamura & Steinsson (2014). Mechanism to explore: weaker fiscal feedback because informal workers do not pay income or payroll taxes.

### Contribution Relative to Existing Literature

- **From cross‐country to within‐country causality.**  
  Colombo et al. (2024) show lower multipliers in high‑informality countries using forecast‑error identification at the national level. I would like to exploit *within‑country* variation, to hold national institutions, exchange‑rate regime, and other important elements constant.

- **Cleaner identification.**  
  Age‑based cash‑transfer rollouts provide a locality-level shock potentially unrelated to informality and economic conditions (I'm thinking that this share of old population was affected by previous conditions but not current).

- **Micro mechanisms.**  
  Household survey data allow us to decompose spending responses, labor shifts, and formal sector, shedding light on the channels Colombo et al. can only infer from aggregate data.

---
