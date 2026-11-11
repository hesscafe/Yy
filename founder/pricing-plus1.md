# What if every drink costs $1 more?

Menu tested: espresso drinks $6–8, Americano $5, plain matcha $8, chai $7, signature drinks $8.50. Pastries stay at $6. Same 20 simulated buyers (seed 320801), same offer (`pitch-plus1.md`, results in `panel-plus1/`). CFO run in `cfo-plus1.md` (inputs `numbers-plus1.json`), at the same guessed 60 drinks a day.

## Buyers

| | Current prices (v2) | +$1 |
|---|---|---|
| Buy | 13 of 20 (65%) | **11 of 20 (55%)** |
| Purchases in the first month | 31 | **28 (−10%)** |
| Weekday commuters | 3 of 7 | 3 of 7 |
| Weekend visitors | 3 of 5 | **2 of 5** |
| West Village residents | 5 of 6 | **4 of 6** |

**Lost:** P002 (commuter, loyal to their café) and P019 (weekend visitor, chose Matchaful). Several who still buy now say the $8 plain matcha is past their "getting expensive" point (P014, P003, P016). P004 and P008 still pass on price.

**Price answers moved up with the menu:** median "getting expensive" went from $7.50 to $8.00 and "too expensive" from $9 to $10. Buyers anchor to the prices they're shown, so this may flatter the higher menu. The new acceptable range is $4.02–$8.50, and the $8.50 signature drinks sit right at its top edge.

## Money (CFO tool)

| | Current | +$1 |
|---|---|---|
| Average price | $6.31 | $7.31 |
| Left per drink | $3.07 (49%) | **$3.74 (51%)** |
| Year 1 profit at 60 a day | $50,203 | **$61,526** |
| Year 1 at −10% drinks (what the panel suggests) | | **$55,205** |
| Year 1 at −15% drinks | | $52,045 |
| Year 1 at −20% drinks | | $48,885 |

**The line:** the +$1 menu earns more as long as you lose **fewer than about 18% of drinks**. The panel suggests about 10% fewer purchases, so the +$1 menu comes out about **$5,000 ahead** in year 1 (about $2,500 each, or about $1.30 an hour more).

## Recommendation

- **Not all at once.** The gain is small, and the drop falls on the people you most need early (weekend visitors and residents), plus it weakens the "cheaper than Matchaful" story.
- **Raise where buyers don't mind:**
  - Regular espresso drinks +$1 ($6–8), in line with nearby specialty coffee.
  - Signature drinks at $8 (the original price), not $8.50.
  - Plain matcha stays at $7. It's the drink you're asking people to taste and compare with Matchaful, and the one buyers say is already near their limit.
  - The Americano stays at $4. It's the commuter hook.
- **Test it for real** in the 2-week test (`launch.md`): week 1 at current prices, week 2 at the higher prices. Compare drinks a day and money left per day.
