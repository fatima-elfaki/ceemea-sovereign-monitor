# Fact-check of sample_brief.md (18 Nov 2026)

I checked each claim in the LLM-generated morning note against published sources.

**Result:** of 10 claims checked, 7 are confirmed and 3 have problems:
- **1 wrong cause:** two separate headlines were merged into a false causal link.
- **1 unconfirmed figure.**
- **1 possibly out of date.**

6 claims were not checked.

| Country | Claim in brief | Status | Finding |
|---|---|---|---|
| South Africa | Rand at a seven-month low | ✅ Confirmed | Reported 14 Nov 2026 (BusinessTech) |
| South Africa | Rand weak *on* post-election coalition talks | ⚠️ Wrong cause | The rand's fall was attributed to US inflation data, weaker metals prices and dollar strength. ANC coalition talks were a separate headline the model linked causally. |
| South Africa | Headline inflation 5.2% | ❓ Not confirmed | October CPI was due for release on 18 Nov; figure not found in sources checked |
| Poland | Central bank froze Constitutional Tribunal payments | ✅ Confirmed | NBP suspended payment orders from the Tribunal's accounts (multiple sources) |
| Poland | Government accuses the central bank of politicisation | ✅ Confirmed | Finance Minister Domański said the NBP should not enter a political conflict |
| Poland | Dispute involves the presidency | ✅ Confirmed | President Nawrocki entered the Tribunal's headquarters |
| Turkey | Central bank raised inflation targets / extended disinflation path | ✅ Confirmed (nuance) | 12 Nov inflation report: year-end 2026 forecast raised to 29.5%; end-2027 and end-2028 interim targets raised to 21% and 13.5% |
| Egypt | EBRD lent $100m to National Bank of Egypt | ⚠️ Possibly stale | EBRD–NBE $100m MSME loans exist, but the most recent EBRD Egypt deal found (2 Nov 2026) was a $100m investment in the Banque du Caire IPO. The headline may be recycled. |
| Saudi Arabia | Fitch sees tighter bank liquidity as lending outpaces deposits | ✅ Confirmed | Fitch (9 Nov 2026): liquidity "adequate but less abundant", lending outrunning deposits |
| Kazakhstan | IMF forecasts faster growth in 2027 | ✅ Confirmed | IMF October WEO: 4.4% in 2026, 4.9% in 2027 |

**Not checked:** Turkey (prosecutor probe, gold-price slide, JPMorgan upgrade), Egypt (Suez Canal recovery), Africa rates (Bloomberg), Kazakhstan (Middle Corridor), Nigeria (Cardoso on NNPCL; a CBN–NNPCL meeting is reported but undated).

## What this shows about the tool

- **Most claims hold up.** The "use only the headlines provided" rule kept the model from inventing facts.
- **The main failure is causal linking.** The model joined two unrelated headlines into "rand weak on coalition talks". A human analyst would check a causal claim before passing it on. Next step: require the prompt to cite the headline behind each bullet, so every claim can be traced.
- **Headline-only input can surface stale news.** Google News can return older articles. Next step: filter by publication date and pass article dates to the model.
- **The World Bank snapshot lags.** The brief used 34.9% for Turkish inflation (2025 annual average); the latest monthly reading was about 30%.

## Sources
- [BusinessTech: rand seven-month low, ANC coalition talks (14 Nov 2026)](https://businesstech.co.za/news/?p=884323)
- [Hungarian Conservative: NBP suspends Tribunal payments; Domański accusation](https://www.hungarianconservative.com/?p=88926)
- [Informat.ro: NBP halts Tribunal payments; President Nawrocki](https://informat.ro/en/international/poland-central-bank-cuts-funding-to-constitutional-tribunal-148678)
- [Daily Sabah: CBRT raises inflation forecasts (12 Nov 2026)](https://www.dailysabah.com/business/economy/turkish-central-bank-revises-2026-2027-inflation-forecasts-upward/amp)
- [IFC: Banque du Caire IPO with EBRD (2 Nov 2026)](https://www.ifc.org/en/pressroom/2026/ifc-partners-with-banque-du-caire-to-expand-finance-for-egyptian-businesses)
- [EnterpriseAM: Fitch on Saudi bank funding (9 Nov 2026)](https://enterpriseam.com/ksa/2026/11/09/saudi-banks-face-years-of-pricier-funding-as-lending-outpaces-deposits-fitch-warns/)
- [Euronews: IMF Kazakhstan growth forecast (6 Nov 2026)](https://www.euronews.com/2026/11/06/kazakhstans-growth-to-pick-up-in-2027-despite-geopolitical-tensions-imf-says)
