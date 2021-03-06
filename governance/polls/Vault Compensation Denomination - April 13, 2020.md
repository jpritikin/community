---
title: Vault Compensation Denomination Poll - April 13, 2020
summary: Signal whether to provide compensation to vault holders in the vault's token (ETH/BAT) or in DAI
discussion_link: https://forum.makerdao.com/t/1822
poll_rules: The voter may select to vote for one of the poll options or they may elect to abstain from the poll entirely
options:
   0: Abstain
   1: ETH or BAT (i.e., the asset that was liquidated) 
   2: DAI

---
# Vault Compensation Denomination Poll - April 13, 2020

The Maker Foundation Interim Governance Facilitator has placed a Governance Poll into the [voting system](https://vote.makerdao.com/polling) on behalf of the community which the community can use to signal whether to provide compensation to vault holders in the vault's token (ETH/BAT) or in DAI

This Governance Poll ([FAQ](https://community-development.makerdao.com/makerdao-scd-faqs/scd-faqs/governance)) will be active for 7 days beginning on Monday, April 13 at 4 PM UTC.

## Review

[An initial poll on whether to compensate vault holders has passed.](https://vote.makerdao.com/polling-proposal/qmwfvvguaf8rz8xwgv2cqnzzt9t5h6epzh17qmk2ue99y4)

This poll poses the choice of which token will be used to compensate, namely ETH/BAT or DAI. When vaults are liquidated, assets are sold for DAI to repay the debt. Any remaining assets are returned to the vault. In brief, in ordinary circumstances, vault holders would receive the type of asset that was originally held in the vault.

Arguments for compensation in ETH/BAT:
- Least surprising to vault owners
- Avoids the risk that vault owners feel cheated, compromising the objectives of compensation: happy users, no distortion of symmetry, positive impact on reputation, and future mass adoption.

Arguments for compensation in DAI:
- Most likely, the price of both BAT and ETH will change since the liquidation event. Therefore, a nominal 100% payout will almost certainly result in a different value than would be obtained by payment in ETH/BAT. However, the payout amount can be adjusted to reflect that difference in the planned subsequent poll.
- The complexity of conducting the compensation is reduced since fewer tokens are involved.
- Compensation in DAI avoids DAI/ETH and DAI/BAT volatility risk. The amount of compensation can be fixed to a number in DAI without worrying about the DAI value of ETH and BAT.

To further clarify, we present an example. Suppose there was a vault with 10 ETH of collateral and 692 DAI of debt. The vault came under liquidation when the collaterallization ratio fell to 130% (instead of the requisite 150%) at the price of 90 DAI/ETH.

After the 13% liquidation penalty, the vault owes 782 DAI (692 DAI + 13% of 692 DAI). All of the ETH collateral was auctioned off at 0 DAI/ETH while the debt of 692 DAI was repaid by flop auctions.

At the time of liquidation, 10 ETH sold at 90 DAI/ETH would have yielded 900 DAI. When we subtract the 782 DAI owed, we get **a remainder of 118 DAI or 1.3 ETH** (at the rate of 90 DAI/ETH at the time).

There are two possible scenarios:

1. **If this poll decides that the compensation shall be in ETH**
   - This vault holder could expect a compensation of 1.3 ETH (or a scaled multiple of it, e.g. 1.1x or 0.9x)
   - To provide compensation, Maker would have to purchase this ETH at the current market rate
  
2. **If this poll decides that the compensation shall be in DAI**
   - This vault holder could expect a compensation scaled by 118 DAI
   - Today's DAI/ETH rate is immaterial

### More background discussion

* [Signal Thread: Do we compensate vault holders that were completely liquidated?](https://forum.makerdao.com/t/1713/43)
* [Compensating vault holders that liquidated at 0 bid?!](https://forum.makerdao.com/t/1541)

## Next Steps

This poll does not determine the amount of compensation. An accurate estimate of compensation shall be determined by some other process. The amount of compensation will be further refined by another poll; we might pay 100% of the compensation or some other percentage (e.g. 50% or 200%). Another poll will be needed to determine a X% haircut/multiplier parameter.

---

Additional information about the Governance process can be found in the [Governance Risk Framework: Governing MakerDAO](https://community-development.makerdao.com/governance/governance-risk-framework)

Demos, help and instructional material for the Governance Dashboard can be found at [Awesome MakerDAO](https://awesome.makerdao.com/#voting).

To participate in future Governance calls, please [join us](https://community-development.makerdao.com/governance/governance-and-risk-meetings) every Thursday at 16:00 UTC.

To add current and upcoming votes to your calendar, please see the [MakerDAO Public Events Calendar](https://calendar.google.com/calendar/embed?src=makerdao.com_3efhm2ghipksegl009ktniomdk%40group.calendar.google.com&ctz=America%2FLos_Angeles).
