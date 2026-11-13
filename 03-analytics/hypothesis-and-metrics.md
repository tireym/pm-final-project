# Hypothesis & Success Metrics (Module 3)

## Pre-work · Hypothesis check
- **Role , who you are solving for (from M2):** Katrin, ecommerce lead at a large online retailer that offers Riverty at checkout and is being pitched on the new card.
- **Goal , what this user is ultimately trying to achieve:** The user is ultimately trying to increase revenue at her ecommerce store in a positive and measurable way.
- **Friction / moment of misery , the specific pain blocking their goal:** The lack of access to the data to show that Riverty new card does indeed increase her revenue in some way. Even if positive change is happening, it is only helpful if it can been seen.
- **Current workaround , the external tool or manual process they rely on (M2):** Step	What she does	Likely tool or process (assumed)	Evidence anchor
1	Asks the Riverty account contact for proof of incremental value and gets none	Email or call with the account manager	N-08; B5 is only a backlog item
2	Pulls her own checkout data to see whether Riverty customers convert or spend more than other payment methods	Internal analytics or BI export, manually filtered by payment method	None; this is an assumption
3	Builds a rough comparison of Riverty against other payment methods on fees, conversion and basket size	Spreadsheet	None; assumption
4	Tests whether the card changes behavior, for example by watching whether Riverty checkout share drops once customers hold the card	Manual before/after review	The research can’t show this, since the pilot is invite-only
5	Decides whether to keep Riverty prominent at checkout, demote it, or push a competitor	Internal review, possibly with her payments team	N-08’s “why would my customers still pick you?”
- **Problem Hook , your one-sentence framing of the business crisis (M1):** Riverty will fall behind, losing both consumers and merchants, if it does not keep up with the rest of the industry.
- **Value Proposition , the outcome your initiative promised to deliver (M1):** Riverty can build stronger relationships with both merchants and consumers if it correctly leverages its new banking license.

## Read the evidence in your case
- **Where does your case say people stall or leave? Does that match the friction you wrote in Module 2?:** The majority of users drop between invited and applied. with a smaller, but noticable drop between approved and card_activated.

No, not necessarily. The friction is the ability to measure change, this data is easily measurable. 21.1% of users reaching the card step could support additional revenue as long as that 21.1% increases their spend above and beyond their baseline behavior.
- **What got better or worse in the case, and does that support the workaround your persona uses?:** The Monthly Trend Data
The number of cards issued (active cards) and in use (purchases) is increasing. Purchases and volume_eur, and avg_spend_per_active_card_eur further support this positive direction. Decline_rate_pct is also increasing, suggesting there are some diminishing returns. The initial set of consumers were the most valuable.

This data is not really applicable because it does not measure the friction. While usage of the card is clear, it is unclear whether this usage is real growth of additional business or simply cannibalism of existing business via other payment methods.

The Cohort Data
The cohort data tells a pretty good story, the card retains 55.1% active usership into the 4th month. This is a good indication that some users will indeed be producing additional revenue at the individual merchant, but this is not a guarantee as the data is not merchant specific.
- **Which user in the case is carrying the pain, and is that the person your Module 2 persona describes?:** My persona focuses on the B2B merchant as the user of this product to increase sales. So no, they are not represented in the segment data. 

However, the cohort data presents one important line: segment "light". For my persona, this light BNPL users are prime candidates from whom to receive additional share of wallet. They have already shown interest in credit solutions, but were not entirely satisfied with the existing BNPL solutions. The credit card product provides an new way to capture their business and might address some of the perceived weakness of existing BNPL solutions. A 62% activation rate is not bad for previously like BNPL users, there is clear interest. The remaining data is poorly labeled, as it is unclear whether the spend statistics are pre-card-activation cohort data or post-card-activation spend data. If it is pre-card data, it could be used to compare change in behavior. If it is post-card data, the statics are OK and seems to bring the light user cohort within reach of the medium user cohort. Upgrading 62% of light users to medium users would like make a noticeable positive impact on the merchants top line.

Still, it is unclear how much of that BNPL increase is happing at the B2B merchants shop. i.e. it shows decent improvements for Riverty, but not necessarily the merchant.

## Step 2 · Craft your hypothesis
- **Qualitative evidence (from M2) , quote the specific friction / moment of misery for your persona:** The inability to measure change in revenue.
- **Quantitative evidence (from M3) , name the metric or data point that confirms the pain; cite the number:** The entire dataset proves that pain. That data is simply not merchant specific.
- **Persona , role, goal, and the friction you confirmed in the reconciliation steps:** I confirmed that measuring change in business is hard without going through the credit card statements line by line to understand the spend split between different merchants where the consumer spent money.
- **Problem you are solving , one sentence describing the specific friction this initiative removes:** The credit card data does theoretically provide a comprehensive snapshot of the consumers spending behavior and theoretically allows Riverty to prove to the merchant that share of wallet towards them is increasing, but that data is not found here.
- **Strategic outcome , what behaviour change do you expect, and how does it map to retention / revenue / churn?:** If Riverty were able to show how consumer spending behavior is changing, I would expect the merchants to attempt to push usage and adoption of the card. This is much the same as how merchant push loyalty cards, they provide consumer purchasing data.
- **Primary success metric (initiative signal) , the leading indicator that tells you the gap is closing:** The leading indicator is within the technology behind the purchase. A card is a transaction level payment method that can be used at a variety of locations. It can be used to understand spending behavior not only with the merchant, but also how that merchant stacks up against other parts of the consumers' life.
- **Guardrail metric (product signal) , the metric that must NOT drop; it protects your existing base:** Adoptions rates cannot fall. If adoption rates fall significantly, the share of wallet data would significantly weaken.
- **Decision window , how much time or data before you scale, pivot, or kill? minimum threshold to proceed?:** Ultimately, that share of wallet goal would need to be set by the merchant, not Riverty. However, is adoptions rates fell into the single digits, it would probably be a kill scenario for the program. There is simply not enough applicable data nor sufficiently structure business case to really come to this conclusion at this time.
- **Draft your full hypothesis sentence , one to three sentences; quote the metric, name the persona, name the outcome:** Based on the structure of the credit card product, I believe that making share of wallet calculations easy for the large enterprise merchants will result in additional Riverty credit card adoption. I will protect adoptions rates and will make a go/no-gi decision after a 1 year test window.
