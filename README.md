# oxylabs proxy: what the tiers actually cost, who should buy it, and the $1/GB pay-as-you-go route for smaller jobs

Most people searching "oxylabs proxy" are trying to settle one question: what will this cost me, and is it worth it? The short answer is that Oxylabs residential proxies start at $30 for 5 GB ($6/GB) on the smallest self-service plan and drop to $2.50/GB on the $2,500-a-month, 1 TB tier. There is no true pay-as-you-go option on residential traffic, the prices you see in the navigation don't match the prices on the plan cards, and VAT lands on top of everything.

That's not a knock on the product. It's a large, well-built network used by companies that can absorb a four-figure monthly commitment. It just means the fit matters more here than with cheaper providers, and the numbers below are worth reading before you enter card details.

This breakdown covers what Oxylabs sells under the "proxy" label, the tier ladder as it stands, the contract terms that decide your real bill, and what the same job costs on a per-gigabyte model if you're not running enterprise volume.

## What Oxylabs actually sells

Oxylabs is a Lithuanian company (Vilnius, founded 2015), and it sells both raw IPs and managed scraping infrastructure:

- **Residential proxies** — the flagship product. 175M+ IPs, 195 countries, unlimited concurrent sessions, country/state/city/ZIP/ASN targeting, sticky sessions, a published average response time of around 0.6 seconds and a 99.95% success rate claim. Every self-service residential plan includes 3 proxy users and 10 whitelisted IPs.
- **Datacenter proxies** — shared pools billed per gigabyte, dedicated pools billed per IP. New accounts get five free datacenter IPs for a month; the cheapest dedicated entry is a three-IP plan at $6.75.
- **ISP / static residential** — billed per IP, with a narrower country footprint (around 25 countries) than the rotating residential pool. Prices reported at the 10-IP tier range from roughly $1.20 to $1.60 per IP depending on which Oxylabs page you read.
- **Mobile proxies** — real 3G/4G/5G device IPs, priced per gigabyte on their own ladder.
- **Managed scraping products** — Web Scraper API from $49/month, SERP and e-commerce scrapers, and Web Unblocker billed per gigabyte.

One small clarification that pricing hubs tend to blur: SOCKS5 isn't a separate Oxylabs product with its own price tag. It's a protocol offered on the residential and dedicated datacenter pools, so you pay the relevant pool's rate.

## Oxylabs residential proxy pricing, tier by tier

| Plan | Traffic | Monthly price | Effective rate |
| --- | --- | --- | --- |
| Starter | 5 GB | $30 | $6/GB |
| Basic | 20 GB | $100 | $5/GB |
| Advanced | 125 GB | $500 | $4/GB |
| Corporate | 1 TB | $2,500 | $2.50/GB |

The pattern is simple: the per-gigabyte rate falls as the monthly commitment rises, and the genuinely competitive rates ($4/GB and below) sit behind commitments of $500 to $2,500 a month.

Two things to know before you compare that ladder to a competitor's headline price. First, Oxylabs' own pages have quoted different starting figures for the same residential pool at the same time — a promotional "$4/GB" on some pages against "$6/GB" as what a new self-service buyer actually pays on the Starter plan. Treat the $6/GB as the number that matters for a fresh account. Second, published prices are pre-VAT, and VAT is added at checkout, which in some jurisdictions adds roughly a fifth to every figure above.

There's also a structural quirk: the residential ladder skips volumes other providers sell. Need 50 GB? You're buying a 20 GB plan and topping up, which pushes your effective rate back toward the Basic tier rather than the halfway point between Basic and Advanced.

## The contract terms that decide your real bill

Rates are the visible part. These are the parts that catch people:

- **Refund window.** Self-service refunds must be requested within three calendar days of your first transaction, with no more than 20% of traffic consumed (10% on enterprise plans). Processing takes up to 15 business days. If you plan to evaluate properly over two weeks, the window has closed before you finish.
- **A published blocked-target list.** Oxylabs restricts its residential network from a list of targets, including Apple domains, banking and financial institutions, some Google properties, government sites, streaming, ticketing and mailing services. The restriction applies regardless of which residential plan you buy, including the $2,500 one. If your target is on that list, price comparison is pointless.
- **KYC before some features.** Verification gates advanced residential filters and certain restricted targets, and onboarding delays measured in days are commonly reported.
- **No real pay-as-you-go on residential.** Every published residential tier is a monthly plan of pre-purchased gigabytes. If your scraping runs heavy for a week and quiet for three, you're still buying the full month. True per-gigabyte billing exists on the shared datacenter pool only.

The free-tier picture is mixed too. The five free datacenter IPs are genuinely free and last a month. Residential has no free tier; the trial is one-time and granted through a form or email request rather than a self-service button.

## Where Oxylabs is the right call, and where it isn't

Buy it if your workload is steady, your targets aren't on the restricted list, and your monthly spend sits comfortably in the hundreds or thousands. At 125 GB the rate is $4/GB, at 1 TB it's $2.50/GB, and what you're paying for on top of the IPs is real: ISO/IEC 27001:2022 and SOC 2 certification, Lloyd's insurance coverage, 24/7 support, a named account manager, and a pool large enough that address repetition isn't your bottleneck. Independent reviewers rate it highly for large teams — PCMag names it among the best proxy services of 2026, and Proxyway has given it a Best Enterprise Provider award.

The picture changes below roughly 100 GB a month. At 5 GB you're at $6/GB, twelve times what a pay-as-you-go provider charges for the same job, and you have no way to buy a single gigabyte without a monthly plan. Trustpilot ratings sit around 3.7/5 across roughly 713 reviews, and the split is unusually bimodal: heavy five-star reviews from managed accounts, one-star reviews clustered around refund windows and onboarding. Those two groups are describing the same product from opposite ends of the same tier ladder.

If you're testing, running an intermittent project, or scraping a few dozen gigabytes a month, you're paying for enterprise infrastructure you won't use. That's usually where people start looking at cheaper per-gigabyte networks — and it's the case this article's numbers can actually help with.

## The per-gigabyte alternative: DataImpulse at $1/GB

DataImpulse is the provider to look at if the tier ladder above is the obstacle. Its model strips out the subscription entirely: residential traffic at **$1/GB**, datacenter at $0.50/GB, mobile at $2/GB, with a $5 minimum purchase and no expiry on traffic you've bought. Country targeting is included in the base rate; city, ZIP and ASN filters are a paid add-on. It supports HTTP/HTTPS and SOCKS5, rotating and sticky sessions, and both username/password and IP whitelist authentication.

Pool size is where the honest trade-off lives. DataImpulse advertises 90M+ ethically sourced residential IPs across 195 countries and 16M+ mobile IPs. One independent test that measured live addresses across the US, UK, France, Canada and Germany returned about 172,900 active IPs for DataImpulse against 306,400 for the deepest network in the same test — roughly 60% of the depth, drawn from fewer distinct networks. On ordinary targets at moderate volume that won't be your constraint. On targets that already treat you as hostile, it will.

Rates come down at volume: residential $0.80/GB and datacenter $0.45/GB on the 1 TB tiers.

### All DataImpulse plans

| Product | Plan | Traffic | Price | Effective rate | Get it |
| --- | --- | --- | --- | --- | --- |
| Residential | Pay-as-you-go | any volume | from $5 | $1.00/GB | [ Start with 5 GB for $5](https://bit.ly/dataimPulse) |
| Residential | Volume | 1 TB+ | $800+ | $0.80/GB | [ Unlock the 1 TB rate](https://bit.ly/dataimPulse) |
| Datacenter | Intro | 10 GB | $5 | $0.50/GB | [ Try datacenter traffic](https://bit.ly/dataimPulse) |
| Datacenter | Basic | 100 GB | $50 | $0.50/GB | [ Buy 100 GB](https://bit.ly/dataimPulse) |
| Datacenter | Advanced | 1 TB | $450 | $0.45/GB | [ Take the 1 TB tier](https://bit.ly/dataimPulse) |
| Datacenter | Custom | 5 TB+ | from $2,250 | custom | [ Request a quote](https://bit.ly/dataimPulse) |
| Mobile | Intro | 2.5 GB | $5 | $2.00/GB | [ Test mobile IPs](https://bit.ly/dataimPulse) |
| Mobile | Basic | 25 GB | $50 | $2.00/GB | [ Buy 25 GB of mobile](https://bit.ly/dataimPulse) |
| Mobile | Advanced | 1 TB | $1,600 | $1.60/GB | [ Take the mobile 1 TB tier](https://bit.ly/dataimPulse) |
| Mobile | Custom | 5 TB+ | from $8,000 | custom | [ Talk to sales](https://bit.ly/dataimPulse) |
| Premium residential | Entry | 1 GB | $5 | $5.00/GB | [ Try premium residential](https://bit.ly/dataimPulse) |
| Premium residential | Basic | 10 GB | $50 | $5.00/GB | [ Buy 10 GB premium](https://bit.ly/dataimPulse) |
| Premium residential | Custom | 5 TB+ | from $20,000 | custom | [ Request enterprise pricing](https://bit.ly/dataimPulse) |

Premium residential adds a dedicated account manager and includes granular targeting without the surcharge; volume discounts on it start at the 1 TB mark.

Two billing details worth checking before you buy. DataImpulse has no free trial in the strict sense — everything starts with a $5 minimum — but Intro plans carry a 7-day money-back guarantee on card payments if you've used less than 80% of the traffic. Crypto purchases on Intro plans aren't refundable. That's a narrower guarantee than "try it free," and a far wider window than Oxylabs' three days.

## Same volume, two bills

Here's what identical workloads cost on each model, using each provider's published rates and excluding VAT where applicable:

| Traffic per month | Cheapest Oxylabs route | Oxylabs cost | DataImpulse cost |
| --- | --- | --- | --- |
| 5 GB | Starter (5 GB) | $30 | $5 |
| 20 GB | Basic (20 GB) | $100 | $20 |
| 100 GB | Advanced (125 GB, nearest tier) | $500 | $100 |
| 1 TB | Corporate (1 TB) | $2,500 | $800 |

The gap narrows as volume grows, which is the expected shape: pay-as-you-go wins comfortably at the bottom, and Oxylabs' economics catch up when you're committing thousands a month and getting compliance documentation, SLAs and managed scraping tools in return. CNET's review noted that only Webshare and DataImpulse undercut Oxylabs on 1 TB residential pricing, with the caveat that both run smaller pools.

For a lot of teams the practical answer isn't either/or. Managed scrapers and enterprise SLA work on Oxylabs, high-volume raw proxy traffic on a cheaper per-gigabyte pool.

## Getting set up in a few minutes

If you're going the pay-as-you-go route, the onboarding is deliberately dull, which is the point:

1. Create an account and add funds. The minimum is $5, which buys 5 GB of residential, 10 GB of datacenter or 2.5 GB of mobile traffic on the Intro tiers.
2. Choose your proxy type in the dashboard. Residential, premium residential, mobile and datacenter all draw on the same balance.
3. Generate credentials. Username/password and IP whitelist both work across all four product types.
4. Format your endpoint. The gateway is `gw.dataimpulse.com`, port 823 for rotating HTTP/HTTPS sessions and port 824 for SOCKS5. Country targeting goes in the username as `user_country-us`; sticky sessions use a session ID in the username and can be held for 1 to 120 minutes.
5. Point it at your target. Country selection is included in the rate; state, city, ZIP and ASN filters are billed as an add-on.

Nothing expires. If you buy 20 GB and use 6 GB this month, the other 14 GB are waiting whenever the project resumes — which is the single biggest practical difference from a monthly tier that resets.

[👉 Open an account and start at $1/GB pay-as-you-go](https://bit.ly/dataimPulse)

## FAQ

**Does Oxylabs have a free trial?**
Datacenter proxies come with five free IPs valid for one month on signup, and the managed scraping products carry a trial badge inside the dashboard. Residential has no free tier, and the one-time trial runs through a form or email request rather than a self-service button.

**Does Oxylabs offer true pay-as-you-go?**
On the shared datacenter pool, yes. Residential is sold as monthly tiers of pre-purchased gigabytes, so a spiky workload pays for traffic it doesn't pull.

**What's the cheapest Oxylabs alternative for residential proxies?**
On the same per-gigabyte model, DataImpulse at $1/GB with a $5 minimum is one of the lowest published entry points in the market. You give up the enterprise SLA, compliance documentation and the largest pool depth, and you get a much lower bill if you're under a few hundred gigabytes a month.

**Can I use SOCKS5 on either provider?**
Oxylabs offers SOCKS5 on its residential and dedicated datacenter pools. DataImpulse supports HTTP/HTTPS and SOCKS5 across its product types, on a separate port.

**Do unused gigabytes expire?**
On DataImpulse, purchased traffic never expires and your balance rolls over. On Oxylabs, residential tiers are monthly and unused traffic follows the plan cycle.

**Which one should you pick?**
If you're scraping at enterprise volume with compliance requirements, fixed monthly budgets and no interest in managing your own scraper stack, Oxylabs is built for exactly that and priced accordingly. If you want to pay for the gigabytes you actually use, with no subscription, no sales call and a refund window longer than 72 hours, $1/GB is the simpler arithmetic — and the pool is big enough for most ordinary targets, just not the deepest one on the market.
