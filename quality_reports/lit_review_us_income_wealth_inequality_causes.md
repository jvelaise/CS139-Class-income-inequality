# Literature Review: Why Has Income and Wealth Inequality Risen in the United States?

**Date:** 2026-11-11
**Query:** "I am researching why wealth and income inequality has increased in the USA" (run via `.claude/skills/lit-review`)

> **Scope and sources.** This review relies only on web searches. The repo has no `master_supporting_docs/supporting_papers/` folder and no `.bib` file. Publication details (journal, volume, pages, DOI) and headline findings were checked against the journal pages, NBER, RePEc/IDEAS and author-hosted PDFs that the searches returned. Federal Reserve and FRED data hosts are **blocked** in this session's network policy, so no current Distributional Financial Accounts (DFA) value is quoted. Pull it yourself (see Suggested Next Steps). Each item is labeled as a working paper or a published article.

---

## Summary

The research agrees on the direction of change: since about 1980, US pre-tax income and wealth have become much more concentrated at the top, after the mid-century "Great Compression". It disagrees about **how large the rise is** and **which mechanisms matter most**. On size, Piketty, Saez and Zucman (2018) find that the bottom half's pre-tax income stagnated at about $16,000 per adult from 1980 to 2014, while average income grew about 60%. Auten and Splinter (2024) argue that once tax-base changes, missing income and taxes and transfers are accounted for, after-tax top shares barely changed. Piketty, Saez and Zucman's 2024 comment replies that the two series are similar in level and trend once assumptions are aligned. Wealth shows a parallel split: the capitalization estimates of Saez and Zucman (2016) against the heterogeneous-returns estimates of Smith, Zidar and Zwick (2023). Both find rising top wealth shares. They disagree on the level and the slope.

The causal research splits into two broad explanations, which are not mutually exclusive. **Market forces** explain the labor-earnings side: skill-biased technical change and the slowdown in college-graduate supply (Goldin and Katz 2008), task-displacing automation (Acemoglu and Restrepo 2022), trade shocks (Autor, Dorn and Hanson 2013), and growing pay gaps between firms tied to worker sorting (Song et al. 2019). **Institutions and policy** explain the top and the lower tail: union decline (Farber et al. 2021), the falling real minimum wage (Autor, Manning and Smith 2016), and lower top tax rates, which raise the payoff to bargaining for higher pay (Piketty, Saez and Stantcheva 2014). Hoffmann, Lee and Lemieux (2020) conclude that **labor-earnings inequality is the main proximate driver** of rising US income inequality, with capital income playing a modest added role.

**Wealth inequality has partly separate drivers.** These include differences in portfolio composition combined with asset-price swings (Kuhn, Schularick and Steins 2020), higher returns at the top (Smith, Zidar and Zwick 2023), declining interest rates that raise the value of long-duration assets held by the rich (Greenwald et al., working paper), the saving behavior of top earners (Saez and Zucman 2016; Mian, Straub and Sufi, working paper), and racially unequal starting points and capital gains (Derenoncourt et al. 2024). Recent work also finds that the lower part of the wage distribution **compressed** after the pandemic (Autor, Dube and McGrew, working paper). Not every component of inequality has risen monotonically, and labor-market tightness matters.

---

## Key Papers

Ordered roughly by relevance to "why did inequality rise".

### Piketty, Saez & Zucman (2018) — Distributional National Accounts
- **Main contribution:** Distributes 100% of US national income across adults, so growth by income group adds up to macro growth.
- **Method:** Combines tax microdata, surveys and national accounts (1913–2014). *QJE* 133(2): 553–609.
- **Key finding:** Average pre-tax real national income per adult rose about 60% from 1980 to 2014, while the bottom 50% stagnated at about $16,000. The bottom half's share fell from about 20% of national income in 1980.
- **Relevance:** The benchmark series that most causal work and public debate refer to.

### Auten & Splinter (2024) — Using Tax Data to Measure Long-Term Trends
- **Main contribution:** The main challenge to the size of the post-1980 rise in top income shares.
- **Method:** National-income-based estimates that adjust for tax-base changes (such as the 1986 Tax Reform Act), social changes like falling marriage rates, and missing income. *JPE* 132(7): 2179–2227.
- **Key finding:** Top pre-tax shares are lower and rose less than in other tax-data studies. Higher transfers and more progressive taxes left **after-tax top shares little changed**. Piketty, Saez and Zucman's 2024 comment (World Inequality Lab Technical Note 2024/04) argues the estimates converge with PSZ in level and trend over 1979–2019 once assumptions are clarified. It also criticizes the Auten–Splinter treatment of untaxed capital income. *(A ~0.4 pp figure for that effect appeared in one search summary but could not be verified against the text, so it is omitted.)*
- **Relevance:** Any causal claim has to say which measure it explains: pre-tax or post-tax, top 1% or Gini.

### Hoffmann, Lee & Lemieux (2020) — Growing Income Inequality in the US and Other Advanced Economies
- **Main contribution:** A decomposition survey that compares the US with Europe.
- **Method:** Decomposes income inequality into labor and capital sources and into education, occupation and location. *JEP* 34(4): 52–78.
- **Key finding:** Growing labor-earnings inequality is the main driver. Capital income adds a modest amount. Education gaps and composition explain much of the US trend. Inequality rose fast in Germany, Italy and the UK but not in France.
- **Relevance:** A balanced framing to anchor the paper's argument. The variation across countries is a useful test of purely technological explanations.

### Acemoglu & Restrepo (2022) — Tasks, Automation, and the Rise in US Wage Inequality
- **Main contribution:** A task framework that links wage changes for demographic groups to task displacement from automation.
- **Method:** 500 demographic groups (Census/ACS). Industry labor-share declines are attributed to adoption of robots, specialized software and dedicated machinery. *Econometrica* 90(5): 1973–2016.
- **Key finding:** **50–70%** of changes in the US wage structure over four decades are accounted for by relative wage declines among groups specialized in routine tasks in rapidly automating industries. Offshoring contributes much less.
- **Relevance:** The strongest quantitative claim for technology as a cause. The sample largely predates AI.

### Goldin & Katz (2008) — The Race between Education and Technology
- **Main contribution:** A supply–demand–institutions model of the college wage premium from 1890 onward.
- **Method:** Long-run series of educational wage differentials (Harvard University Press). Extended by Autor, Goldin and Katz (2020, *AEA P&P*).
- **Key finding:** Steady growth in demand for skilled workers, combined with a **post-1980 slowdown in the growth of college-educated labor supply**, explains much of the surge in the college premium from 1980 to 2005.
- **Relevance:** The classic skill-biased technical change account, which points to education policy as a lever.

### Song, Price, Guvenen, Bloom & von Wachter (2019) — Firming Up Inequality
- **Main contribution:** Shows how much of the rise in earnings inequality happens within firms versus between them.
- **Method:** Matched employer–employee data from the Social Security Administration, 1978–2013. *QJE* 134(1): 1–50.
- **Key finding:** About two-thirds of the rise in the variance of log earnings is **between firms**, driven by worker sorting and segregation, not by firm-specific pay policies.
- **Relevance:** Shifts the question toward labor-market sorting and firm structure.

### Autor, Dorn, Katz, Patterson & Van Reenen (2020) — The Fall of the Labor Share and the Rise of Superstar Firms
- **Main contribution:** Links the falling labor share to reallocation toward high-markup, low-labor-share firms.
- **Method:** US Economic Census panel data, 1982 onward. *QJE* 135(2): 645–709.
- **Key finding:** Industries where concentration rose most saw the largest labor-share declines.
- **Relevance:** Connects market structure to the split between labor and capital income.

### Farber, Herbst, Kuziemko & Naidu (2021) — Unions and Inequality over the Twentieth Century
- **Main contribution:** New union microdata going back to 1936.
- **Method:** About 980,000 observations, mostly from Gallup surveys. *QJE* 136(3): 1325–1385.
- **Key finding:** The household union premium was stable at 10–20 log points. Mid-century unions disproportionately drew less-educated and non-white workers, so union decline plausibly widened inequality.
- **Relevance:** The leading modern evidence for the institutions explanation.

### Autor, Manning & Smith (2016) — The Contribution of the Minimum Wage to US Wage Inequality
- **Main contribution:** Re-estimates how much the falling real minimum wage contributed to lower-tail inequality.
- **Method:** Cross-state variation in minimum wages, 1979–2012. *AEJ: Applied* 8(1): 58–99.
- **Key finding:** The minimum wage narrows lower-tail inequality, but **by much less than earlier estimates** (such as Lee 1999). Some apparent spillovers may be measurement artifacts.
- **Relevance:** A partial check on purely institutional explanations.

### Piketty, Saez & Stantcheva (2014) — Optimal Taxation of Top Labor Incomes
- **Main contribution:** Separates top earners' responses to tax rates into labor supply, avoidance and compensation-bargaining channels.
- **Method:** International panel of top tax rates and top income shares, plus US CEO pay data. *AEJ: Economic Policy* 6(1): 230–71.
- **Key finding:** Top tax rate cuts are associated with **rising top 1% pre-tax income shares but not faster growth**. CEO "pay for luck" is more common when top rates are low.
- **Relevance:** The main mechanism linking policy to rising top incomes.

### Kuhn, Schularick & Steins (2020) — Income and Wealth Inequality in America, 1949–2016
- **Main contribution:** Joint income–wealth distributions going back to 1949.
- **Method:** Archival Survey of Consumer Finances (SCF) waves. *JPE* 128(9): 3469–3519.
- **Key finding:** Middle-class wealth is mostly leveraged housing, while the top holds business equity. **Asset prices** therefore drive wealth inequality: housing booms compress it, and stock booms widen it.
- **Relevance:** Explains why wealth and income inequality can diverge, for example after 2008.

### Saez & Zucman (2016) — Wealth Inequality in the United States since 1913
- **Main contribution:** Wealth series built by capitalizing income tax data.
- **Method:** Tax returns combined with macro balance sheets, validated in SCF, estate and foundation data. *QJE* 131(2): 519–578.
- **Key finding:** The top 0.1% wealth share rose from **7% (1978) to 22% (2012)**, driven by rising top incomes and growing inequality in saving rates.
- **Relevance:** The high-end benchmark for top wealth.

### Smith, Zidar & Zwick (2023) — Top Wealth in America
- **Main contribution:** Capitalization that allows for different returns within asset classes.
- **Method:** Linked administrative tax data. *QJE* 138(1): 515–573.
- **Key finding:** Fixed-income returns at the top are about 3.5 times the average, so assuming equal returns overstates top wealth. Top shares still rose substantially from 1989 to 2016. The working-paper abstract reports a top 0.1% share of 15.7% in 2016.
- **Relevance:** The main lower-bound alternative to Saez and Zucman (2016).

### Derenoncourt, Kim, Kuhn & Schularick (2024) — Wealth of Two Nations
- **Main contribution:** A continuous series of the white-to-Black wealth ratio, 1860–2020.
- **Method:** Census data, state tax records and historical SCF, plus a model of wealth accumulation. *QJE* 139(2): 693–750.
- **Key finding:** Convergence stalled after 1950 and the gap has **widened since the 1980s**, with differences in capital gains now the dominant force.
- **Relevance:** Shows how rising asset prices interact with unequal starting wealth.

### Autor, Dorn & Hanson (2013) — The China Syndrome
- **Main contribution:** Local-labor-market effects of Chinese import competition.
- **Method:** Shift-share exposure across commuting zones, 1990–2007. *AER* 103(6): 2121–2168.
- **Key finding:** Higher imports caused unemployment, lower participation and lower wages in exposed areas, accounting for about a quarter of the aggregate decline in manufacturing employment.
- **Relevance:** Trade concentrates losses in particular places. Its contribution to *aggregate* inequality is less settled (see Gaps).

---

## Thematic Organization

### Theoretical Contributions
- **Supply and demand for skills (canonical model):** Katz and Murphy (1992), Goldin and Katz (2008). The college premium depends on demand for skilled workers relative to their supply.
- **Task-based models:** Acemoglu and Autor (2011) and Acemoglu and Restrepo (2022) let technology *displace* worker groups from tasks. This explains polarization and real wage declines, which the canonical model cannot.
- **Bargaining and rent-sharing at the top:** In Piketty, Saez and Stantcheva (2014), top tax rates affect pre-tax inequality by changing the payoff to bargaining over pay.
- **Wealth dynamics:** Piketty (2014) argues that a gap between r and g concentrates wealth. Gomez (2023, *Econometrica* 91(3): 979–1024) gives an accounting decomposition of top-share growth into *within* (existing fortunes growing), *between* (new fortunes entering) and *demography*. Greenwald et al. use incomplete-markets models with portfolio duration, in which falling interest rates raise financial wealth inequality.

### Empirical Findings
| Mechanism | Principal evidence | Direction and size | Main tension |
|---|---|---|---|
| Automation and tasks | Acemoglu & Restrepo 2022 | 50–70% of wage-structure change | Depends on attributing labor-share declines to automation |
| Skill supply and demand | Goldin & Katz 2008; Autor, Goldin & Katz 2020 | Large for the college premium, 1980–2005 | Card & DiNardo 2002: timing puzzles |
| Firms and sorting | Song et al. 2019 | ~2/3 of the variance rise is between firms | Sorting, not firm pay premia |
| Concentration | Autor et al. 2020 | Concentration ↔ falling labor share | Kehrig & Vincent 2021: transient "shooting stars" |
| Trade | Autor, Dorn & Hanson 2013 | Large local effects | Aggregate share unclear |
| Unions | Farber et al. 2021 | 10–20 log point premium; density fell | DiNardo & Lee 2004: near-zero RD wage effects |
| Minimum wage | Autor, Manning & Smith 2016 | Real but smaller than earlier estimates | Spillovers may be measurement artifacts |
| Top tax rates | Piketty, Saez & Stantcheva 2014 | Cuts ↔ higher top shares, no growth gain | Cross-country correlation, not a clean experiment |
| Asset prices and portfolios | Kuhn, Schularick & Steins 2020 | Stock booms raise wealth inequality | — |
| Returns heterogeneity | Smith, Zidar & Zwick 2023 | Top earns ~3.5× average fixed-income return | Lowers the *level* of top wealth |
| Interest rates | Greenwald et al. (WP) | 75%–100% of the rise in financial wealth inequality, depending on draft | Total wealth including human capital rises much less |
| Saving of the rich | Saez & Zucman 2016; Mian, Straub & Sufi (WP) | Rising top saving financed household and government debt | — |
| Race | Derenoncourt et al. 2024 | Gap widening since the 1980s | — |

### Methodological Innovations
- **Distributional national accounts** (PSZ 2018; Auten & Splinter 2024). These reconcile micro data with macro totals, and the allocation rules drive much of the disagreement.
- **Real-time distributional statistics** (Blanchet, Mouillet, Saez & Zucman 2026, *Journal of Public Economics* 260; first circulated as NBER WP 30229 in 2022 by Blanchet, Saez & Zucman). Quarterly estimates are published at realtimeinequality.org.
- **Capitalization with heterogeneous returns** (Smith, Zidar & Zwick 2023).
- **Matched employer–employee variance decompositions** (Song et al. 2019).
- **Shift-share and exposure designs** (Autor, Dorn & Hanson 2013; Acemoglu & Restrepo). Identification depends on which industries carry the instrument's weight.
- **Regression discontinuity at union elections** (DiNardo & Lee 2004).
- **New historical microdata:** Gallup union data (Farber et al.), archival SCF (Kuhn et al.), 19th-century tax records (Derenoncourt et al.).

### Open Debates
1. **How much did top shares rise?** PSZ versus Auten–Splinter for income, and Saez–Zucman versus Smith–Zidar–Zwick for wealth.
2. **Technology versus institutions.** Task displacement claims most of the wage-structure change. The union, minimum-wage and tax research claims a substantial share. The decompositions are not additive, so the shares can't simply be summed.
3. **Does concentration reflect market power or efficiency?** Superstar firms versus transient productive "shooting stars".
4. **Financial versus total wealth.** Greenwald et al. find that counting human wealth weakens the rise at the top.

---

## Gaps and Opportunities

1. **No accepted joint decomposition.** Each mechanism is estimated in its own framework and data. A unified accounting that runs automation, skill supply, unions, the minimum wage and firm sorting through one dataset (for example CPS-ORG with a common counterfactual method) is missing. Without one, shares claimed by different papers can add up to more than 100%.
2. **Aggregate effects of trade.** The China-shock research identifies *relative* local effects. The search found no well-identified aggregate share of national wage inequality due to trade. The searches returned no decomposition that addresses this directly; see the search log below.
3. **The AI era.** Acemoglu and Restrepo's sample essentially predates AI. Whether generative AI widens or compresses wage gaps is an open empirical question, and 2023–2026 data now exist.
4. **Post-2020 reversals.** Wage compression at the bottom after the pandemic (Autor, Dube & McGrew, WP) and the Auten–Splinter update finding fiscal relief offset most of the 2020–22 rise suggest some trends can reverse. Whether the compression lasts as labor markets cool is untested in peer-reviewed work.
5. **Measuring wealth at the top.** Private business valuations, unrealized capital gains and offshore wealth remain poorly measured. Estimates swing with capitalization assumptions.
6. **Causal effect of top tax rates on pre-tax shares within the US.** PSS (2014) rely on cross-country correlation. Clean within-US designs, such as state top-rate changes, are scarce.

### How independent is the support?
- **"Labor-earnings inequality drives income inequality":** Hoffmann, Lee & Lemieux (2020), Song et al. (2019) and Acemoglu & Restrepo (2022) are **3 apparent / 2 independent** sources. Song et al. use SSA administrative data. HLL and AR both rely on Census-family household surveys (CPS/ACS), although they use them differently.
- **"Top income shares rose sharply since 1980":** PSZ (2018), Saez & Zucman (2016) and Blanchet et al. (2026) are **3 apparent / 1 independent**, since all three share the Piketty–Saez–Zucman team and tax-data pipeline. Auten & Splinter, using the same IRS data but different allocations, find a smaller rise. Kuhn et al. use SCF survey data and offer some independent support on the wealth side.
- **"Top wealth shares rose":** Saez & Zucman (2016), Smith, Zidar & Zwick (2023) and Kuhn, Schularick & Steins (2020) are **3 apparent / 2 independent**. SZ and SZZ both capitalize IRS income data, while KSS use the SCF.
- **"Union decline raised inequality":** Farber et al. (2021) is **1 independent** source in this review. Western & Rosenfeld (2011, *ASR*), mentioned earlier in the session, is plausibly independent but was **not re-verified** here.
- **Kuhn–Schularick overlap:** Kuhn and Schularick are coauthors on both Kuhn, Schularick & Steins (2020) and Derenoncourt et al. (2024), and both use the archival SCF. Count them as one source on asset-price channels.

### What went the other way?
- **Skill-biased technical change:** Card & DiNardo (2002, *JLE* 20(4): 733–783) argue that SBTC fails to explain the leveling-off of wage inequality in the 1990s despite continued computer adoption, as well as gender, race and age patterns. Search: "Card DiNardo 2002 skill-biased technological change problems and puzzles".
- **Automation and robots:** A 2026 Zenodo replication of Acemoglu & Restrepo (2020, *JPE*, "Robots and Jobs"), a sister paper to the 2022 *Econometrica* article, reproduces the coefficients exactly. It finds that about 84% of the instrument's Rotemberg weight comes from autos and that exposure-robust first-stage F-statistics are about 6. A separate CeBER working paper argues that the linear effect isn't robust to a squared term. **Neither is peer-reviewed. No direct critique of the 2022 *Econometrica* task-displacement estimate was found.** Search: "Acemoglu Restrepo task displacement replication critique".
- **Unions:** DiNardo & Lee (2004, *QJE* 119(4): 1383–1441) use a regression discontinuity at union elections (1984–1999 drives) and find **wage effects close to zero** for newly organized employers. This conflicts with the cross-sectional union premium, though it estimates a different parameter: new certification on the margin, not established unions. Search: "DiNardo Lee 2004 new unionization regression discontinuity".
- **Superstar firms:** Kehrig & Vincent (2021, *QJE*) find that low labor shares in manufacturing are often *transient* and reflect high productivity, not low wages ("shooting stars"). Evidence in European data is weaker, and one German firm study finds no support for the overhead-cost mechanism. Search: "critique superstar firms labor share Kehrig Vincent".
- **Minimum wage:** Autor, Manning & Smith (2016) is itself the downward revision of Lee (1999).
- **Size of top income growth:** Auten & Splinter (2024), plus their 2025 update covering 2020–22.
- **Wealth:** Smith, Zidar & Zwick (2023) give lower top-wealth levels. Greenwald et al. find total-wealth inequality including human wealth rises much less.
- **Trade:** No null result found for local effects. Galle, Rodríguez-Clare & Yi (2023, *Review of Economic Studies*) quantify the China shock's distributional welfare effects. They find about 13% of the population lose but no significant rise in within-group inequality. Neither they nor Autor, Dorn & Hanson give an aggregate share of national wage inequality. Search: "China shock contribution to US wage inequality small".
- **Top tax rates:** No null result surfaced in this search. Search: "Piketty Saez Stantcheva top tax rates bargaining". Look for within-US evidence before relying on this channel.

---

## Suggested Next Steps

- **Allow Fed data hosts:** add `federalreserve.gov` and `fred.stlouisfed.org` to the session's network allowlist. Then pull the DFA top 1% and bottom 50% net-worth shares (FRED series `WFRBST01134` and `WFRBSB50215`), plus WID (`wid.world`) series for a figure on pre-tax and post-tax top shares.
- **Read in this order:** Hoffmann–Lee–Lemieux (2020) → Auten–Splinter (2024) with the Zucman (2024) comment → Acemoglu–Restrepo (2022) → Song et al. (2019) → Kuhn–Schularick–Steins (2020).
- **Methods to consider for a class project:** DiNardo–Fortin–Lemieux (1996) reweighting decompositions on CPS-ORG to give counterfactual wage distributions with unions and the minimum wage held at 1979 levels. Firpo–Fortin–Lemieux RIF regressions are an alternative.
- **Verify before citing:** working-paper numbers (Greenwald et al., Mian–Straub–Sufi, Autor–Dube–McGrew) change between drafts. For example, the Autor–Dube–McGrew offset is about one-quarter in the March 2023 draft, about one-third in the 2024 draft, and "nearly 40%" in a November 2023 version.
- **Cross-country contrast:** use WID data to compare the US with France, which faces similar technology but has different institutions. This tests technology-only accounts.

---

## BibTeX Entries

Entries marked `% UNVERIFIED` could not be fully confirmed in this session's searches.

```bibtex
@article{piketty2018distributional,
  author  = {Piketty, Thomas and Saez, Emmanuel and Zucman, Gabriel},
  title   = {Distributional National Accounts: Methods and Estimates for the United States},
  journal = {Quarterly Journal of Economics},
  year    = {2018}, volume = {133}, number = {2}, pages = {553--609},
  doi     = {10.1093/qje/qjx043}
}

@article{auten2024income,
  author  = {Auten, Gerald and Splinter, David},
  title   = {Income Inequality in the United States: Using Tax Data to Measure Long-Term Trends},
  journal = {Journal of Political Economy},
  year    = {2024}, volume = {132}, number = {7}, pages = {2179--2227},
  doi     = {10.1086/728741}
}

@techreport{psz2024comment,
  author      = {Piketty, Thomas and Saez, Emmanuel and Zucman, Gabriel},
  title       = {Income Inequality in the United States: A Comment},
  institution = {World Inequality Lab},
  type        = {Technical Note}, number = {2024/04}, year = {2024},
  note        = {September 2024; a 2026 revision exists}
}

@article{hoffmann2020growing,
  author  = {Hoffmann, Florian and Lee, David S. and Lemieux, Thomas},
  title   = {Growing Income Inequality in the United States and Other Advanced Economies},
  journal = {Journal of Economic Perspectives},
  year    = {2020}, volume = {34}, number = {4}, pages = {52--78},
  doi     = {10.1257/jep.34.4.52}
}

@article{acemoglu2022tasks,
  author  = {Acemoglu, Daron and Restrepo, Pascual},
  title   = {Tasks, Automation, and the Rise in {U.S.} Wage Inequality},
  journal = {Econometrica},
  year    = {2022}, volume = {90}, number = {5}, pages = {1973--2016},
  doi     = {10.3982/ECTA19815}
}

@book{goldin2008race,
  author    = {Goldin, Claudia and Katz, Lawrence F.},
  title     = {The Race between Education and Technology},
  publisher = {Belknap Press of Harvard University Press},
  address   = {Cambridge, MA},
  year      = {2008}
}

@article{song2019firming,
  author  = {Song, Jae and Price, David J. and Guvenen, Fatih and Bloom, Nicholas and von Wachter, Till},
  title   = {Firming Up Inequality},
  journal = {Quarterly Journal of Economics},
  year    = {2019}, volume = {134}, number = {1}, pages = {1--50},
  doi     = {10.1093/qje/qjy025}
}

@article{autor2020fall,
  author  = {Autor, David and Dorn, David and Katz, Lawrence F. and Patterson, Christina and Van Reenen, John},
  title   = {The Fall of the Labor Share and the Rise of Superstar Firms},
  journal = {Quarterly Journal of Economics},
  year    = {2020}, volume = {135}, number = {2}, pages = {645--709},
  doi     = {10.1093/qje/qjaa004}
}

@article{farber2021unions,
  author  = {Farber, Henry S. and Herbst, Daniel and Kuziemko, Ilyana and Naidu, Suresh},
  title   = {Unions and Inequality over the Twentieth Century: New Evidence from Survey Data},
  journal = {Quarterly Journal of Economics},
  year    = {2021}, volume = {136}, number = {3}, pages = {1325--1385},
  doi     = {10.1093/qje/qjab012}  % DOI confirmed only via secondary listing
}

@article{autor2016contribution,
  author  = {Autor, David H. and Manning, Alan and Smith, Christopher L.},
  title   = {The Contribution of the Minimum Wage to {US} Wage Inequality over Three Decades: A Reassessment},
  journal = {American Economic Journal: Applied Economics},
  year    = {2016}, volume = {8}, number = {1}, pages = {58--99},
  doi     = {10.1257/app.20140073}
}

@article{piketty2014optimal,
  author  = {Piketty, Thomas and Saez, Emmanuel and Stantcheva, Stefanie},
  title   = {Optimal Taxation of Top Labor Incomes: A Tale of Three Elasticities},
  journal = {American Economic Journal: Economic Policy},
  year    = {2014}, volume = {6}, number = {1}, pages = {230--271},
  doi     = {10.1257/pol.6.1.230}
}

@article{kuhn2020income,
  author  = {Kuhn, Moritz and Schularick, Moritz and Steins, Ulrike I.},
  title   = {Income and Wealth Inequality in America, 1949--2016},
  journal = {Journal of Political Economy},
  year    = {2020}, volume = {128}, number = {9}, pages = {3469--3519},
  doi     = {10.1086/708815}
}

@article{saez2016wealth,
  author  = {Saez, Emmanuel and Zucman, Gabriel},
  title   = {Wealth Inequality in the United States since 1913: Evidence from Capitalized Income Tax Data},
  journal = {Quarterly Journal of Economics},
  year    = {2016}, volume = {131}, number = {2}, pages = {519--578},
  doi     = {10.1093/qje/qjw004}
}

@article{smith2023top,
  author  = {Smith, Matthew and Zidar, Owen and Zwick, Eric},
  title   = {Top Wealth in America: New Estimates under Heterogeneous Returns},
  journal = {Quarterly Journal of Economics},
  year    = {2023}, volume = {138}, number = {1}, pages = {515--573},
  doi     = {10.1093/qje/qjac033}
}

@article{derenoncourt2024wealth,
  author  = {Derenoncourt, Ellora and Kim, Chi Hyun and Kuhn, Moritz and Schularick, Moritz},
  title   = {Wealth of Two Nations: The {U.S.} Racial Wealth Gap, 1860--2020},
  journal = {Quarterly Journal of Economics},
  year    = {2024}, volume = {139}, number = {2}, pages = {693--750},
  doi     = {10.1093/qje/qjad044}
}

@article{autor2013china,
  author  = {Autor, David H. and Dorn, David and Hanson, Gordon H.},
  title   = {The China Syndrome: Local Labor Market Effects of Import Competition in the United States},
  journal = {American Economic Review},
  year    = {2013}, volume = {103}, number = {6}, pages = {2121--2168},
  doi     = {10.1257/aer.103.6.2121}
}

@article{gomez2023decomposing,
  author  = {Gomez, Matthieu},
  title   = {Decomposing the Growth of Top Wealth Shares},
  journal = {Econometrica},
  year    = {2023}, volume = {91}, number = {3}, pages = {979--1024},
  doi     = {10.3982/ECTA16755}
}

@article{card2002skill,
  author  = {Card, David and DiNardo, John E.},
  title   = {Skill-Biased Technological Change and Rising Wage Inequality: Some Problems and Puzzles},
  journal = {Journal of Labor Economics},
  year    = {2002}, volume = {20}, number = {4}, pages = {733--783},
  doi     = {10.1086/342055}
}

@article{dinardo2004economic,
  author  = {DiNardo, John and Lee, David S.},
  title   = {Economic Impacts of New Unionization on Private Sector Employers: 1984--2001},
  journal = {Quarterly Journal of Economics},
  year    = {2004}, volume = {119}, number = {4}, pages = {1383--1441},
  doi     = {10.1162/0033553042476189}
}

@article{kehrig2021micro,
  author  = {Kehrig, Matthias and Vincent, Nicolas},
  title   = {The Micro-Level Anatomy of the Labor Share Decline},
  journal = {Quarterly Journal of Economics},
  year    = {2021}, volume = {136}, number = {2}, pages = {1031--1087},
  doi     = {10.1093/qje/qjab002}
}

@article{galle2023slicing,
  author  = {Galle, Simon and Rodr{\'i}guez-Clare, Andr{\'e}s and Yi, Moises},
  title   = {Slicing the Pie: Quantifying the Aggregate and Distributional Effects of Trade},
  journal = {Review of Economic Studies},
  year    = {2023},
  note    = {% UNVERIFIED volume/pages; identified as ReStud rdac020}
}

@techreport{greenwald2021financial,
  author      = {Greenwald, Daniel L. and Leombroni, Matteo and Lustig, Hanno and Van Nieuwerburgh, Stijn},
  title       = {Financial and Total Wealth Inequality with Declining Interest Rates},
  institution = {National Bureau of Economic Research},
  type        = {NBER Working Paper}, number = {28613}, year = {2021},
  note        = {Later drafts retitled "Wealth Inequality with Declining Interest Rates"; no journal version found}
}

@techreport{mian2020saving,
  author      = {Mian, Atif R. and Straub, Ludwig and Sufi, Amir},
  title       = {The Saving Glut of the Rich},
  institution = {National Bureau of Economic Research},
  type        = {NBER Working Paper}, number = {26941}, year = {2020}
}

@techreport{autor2023unexpected,
  author      = {Autor, David and Dube, Arindrajit and McGrew, Annie},
  title       = {The Unexpected Compression: Competition at Work in the Low Wage Labor Market},
  institution = {National Bureau of Economic Research},
  type        = {NBER Working Paper}, number = {31010}, year = {2023}
}

@article{blanchet2026realtime,
  author  = {Blanchet, Thomas and Mouillet, L{\'e}on and Saez, Emmanuel and Zucman, Gabriel},
  title   = {Real-Time Inequality},
  journal = {Journal of Public Economics},
  year    = {2026}, volume = {260},
  note    = {Article number not confirmed. First circulated as NBER Working Paper 30229 (2022) by Blanchet, Saez and Zucman.}
}

@article{autor2020extending,
  author  = {Autor, David and Goldin, Claudia and Katz, Lawrence F.},
  title   = {Extending the Race between Education and Technology},
  journal = {AEA Papers and Proceedings},
  year    = {2020}, volume = {110}, pages = {347--351},
  doi     = {10.1257/pandp.20201061}
}
```

---

<details>
<summary><strong>Post-Flight Verification</strong>: FAIL → corrected; now PARTIAL</summary>

**Protocol note:** The skill calls for a `claim-verifier` subagent and `.claude/rules/post-flight-verification.md`. Neither exists in this repo, so a general-purpose agent was run in a fresh context. It received only the 27 claims and the verification questions, not the draft text.

**Verifier access limits:** gabriel-zucman.eu, eml.berkeley.edu, nber.org, federalreserve.gov and FRED could not be fetched, and Crossref returned 403. Most checks rest on journal pages, RePEc/IDEAS, AEA, Wiley and Oxford Academic snippets, and on abstracts rather than full texts.

**Initial verdict: FAIL** (1 contradicted, 2 unverifiable, 24 verified).

| Claim | Verifier result | Action taken |
|---|---|---|
| Real-Time Inequality | CONTRADICTED: published as Blanchet, Mouillet, Saez & Zucman (2026), *J. Public Econ.* 260 | Citation and text rewritten |
| PSZ 2024 comment, ~0.4 pp figure | UNVERIFIABLE | Figure removed. Authors confirmed (WIL Technical Note 2024/04) |
| Farber et al. 2021 DOI | Confirmed only via a secondary listing | Flagged in BibTeX |
| Kehrig & Vincent 2021, AGK 2020, Saez & Zucman 2016 details | VERIFIED | `UNVERIFIED` flags removed; DOIs added |
| DiNardo & Lee 2004 DOI | Supplied by verifier | Added |
| Autor–Dube–McGrew offset | Third figure found ("nearly 40%", Nov 2023) | Added to next steps |
| Negative claims (no published critique of AR 2022; no aggregate China-shock share) | VERIFIED by spot-check; Galle, Rodríguez-Clare & Yi (2023) found as related | Added to "What went the other way" |
| All other claims (C1, C2, C4–C9, C11–C19, C22–C24) | VERIFIED | None needed |

**Remaining uncertainty:** the Galle et al. BibTeX volume and pages, the JPubE article number, and the Farber et al. DOI. All are flagged in the BibTeX block. Working papers (Greenwald et al., Mian–Straub–Sufi, Autor–Dube–McGrew) have no journal version as of the verification date.

</details>
