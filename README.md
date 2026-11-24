# vps $2 in Practice: What You Get, What Renews Higher, and Which Evoxt Plan to Buy (All 12 Plans Compared)

A $2 VPS is real, and it is almost always an annual bill divided by twelve: $24 a year works out to $2 a month. In a November 2026 comparison of 37 hosts selling entry plans at $3 or less, the median sign-up price was $2.47/mo and the median renewal price $3.32/mo, and only 4 of those 37 never raise the price. Evoxt, the provider covered here, has no $2 plan at all: its cheapest machine is VM-0.5 at $2.99/mo. What follows is Evoxt's full price list, what the $2–$3 band actually buys from anyone in 2026, and which of those plans is worth your money.

> **Quick picks.** A box that only runs WireGuard, a bot, uptime checks or cron: VM-0.5, $2.99/mo, 1 core / 512 MB / 5 GB. Anything that serves a real site or an app with a database: VM-1, $5.99/mo, 1 core / 2 GB / 20 GB / 500 GB transfer. 👉 [See all 12 Evoxt plans and current prices](https://bit.ly/EvoXt)

## What $2 a month buys from anyone in 2026

The $2–$3 band is where entry plans cluster, and the spread inside it is much wider than the price gap suggests. From the same 37-host comparison:

- Netcup pico G11.5s: $2.52/mo on a one-year term, 1 vCPU, 1 GB RAM, 30 GB SSD.
- CloudCone SSD VPS 1: $2.33/mo on a one-year term, 2 vCPU, 1 GB RAM, 30 GB SSD, 4 TB transfer.
- YetaHost Spark: $2.51/mo month-to-month, 0.5 vCPU, 2 GB RAM, 15 GB NVMe, 1 TB.
- VDSina: $1.78/mo month-to-month, 1 core, 1 GB RAM, 10 GB NVMe, 1 TB.
- AlphaVPS ENTRY: €2.54/mo (€30.50 a year), 2 vCores, 2 GB RAM, NVMe RAID-10, seven EU and US locations.

Two hosts charging roughly $2.50 can hand you 512 MB or 2 GB of RAM, a fourfold difference for the same money. "How much RAM do I get for $2" has no single answer, which is why the plan table matters more than the headline price.

Under $2 proper, the picture narrows. HostAdvice's October 2026 guide describes the typical sub-$2 box as 1 core, 256–512 MB RAM, 5–20 GB of disk and 100–500 GB of monthly bandwidth, with root access and little else. That is still a useful machine: a 512 MB Debian box runs WireGuard, a monitoring agent, a cron job or a chat bot without complaint. It will not run a WordPress site with a page builder.

There is also a specific trap worth naming. One entry plan in the 37-host table is listed at $1.00/mo billed monthly and renews at $7.99/mo, a 699% jump. The monthly-equivalent figure in any ad describes a billing term, not the hardware you keep.

## Evoxt's full plan list and prices

Evoxt's pricing page carries 12 plans, from $2.99 to $95.99 a month, priced in US dollars. All 12 are below.

| Plan | Cores / RAM | Storage | Monthly transfer | Price | Order |
| --- | --- | --- | --- | --- | --- |
| VM-0.5 | 1 / 512 MB | 5 GB | 250 GB | $2.99/mo | [Order VM-0.5](https://bit.ly/EvoXt) |
| VM-0.75 | 1 / 1 GB | 10 GB | 250 GB | $4.99/mo | [Order VM-0.75](https://bit.ly/EvoXt) |
| VM-1 | 1 / 2 GB | 20 GB | 500 GB | $5.99/mo | [Order VM-1](https://bit.ly/EvoXt) |
| VM-1.5 | 2 / 2 GB | 20 GB | 500 GB | $6.95/mo | [Order VM-1.5](https://bit.ly/EvoXt) |
| VM-2 | 2 / 4 GB | 30 GB | 1,000 GB | $11.99/mo | [Order VM-2](https://bit.ly/EvoXt) |
| VM-3 | 4 / 4 GB | 30 GB | 1,000 GB | $14.99/mo | [Order VM-3](https://bit.ly/EvoXt) |
| VM-4 | 4 / 8 GB | 60 GB | 2,000 GB | $23.99/mo | [Order VM-4](https://bit.ly/EvoXt) |
| VM-6 | 8 / 8 GB | 60 GB | 2,000 GB | $29.99/mo | [Order VM-6](https://bit.ly/EvoXt) |
| VM-8 | 8 / 16 GB | 80 GB | 3,000 GB | $47.99/mo | [Order VM-8](https://bit.ly/EvoXt) |
| VM-12 | 16 / 16 GB | 80 GB | 3,000 GB | $60.95/mo | [Order VM-12](https://bit.ly/EvoXt) |
| VM-16 | 16 / 32 GB | 100 GB | 5,000 GB | $95.99/mo | [Order VM-16](https://bit.ly/EvoXt) |

What comes with every plan, according to Evoxt's own product pages:

- Weekly offsite backup at no extra cost. HostAdvice notes that snapshot and backup features are often restricted on sub-$2 plans, so this is not a given in this bracket.
- One IPv4 and one IPv6 address, full root access, Linux or Windows, and a browser-based VNC console.
- VM cloning, monitoring, IP reassignment and sub-accounts from the control panel.
- Resource upgrades on an existing VM without switching plans, which matters if you start at 512 MB.
- Billing from monthly up to 3 years, plus account credit top-ups. Payment by credit or debit card, PayPal, Bitcoin or USDt (Tron).
- The plan sizes are sold in several regions. Premium locations such as Hong Kong and Osaka carry smaller monthly transfer allowances than the standard ones, so check the region selector before checkout.

Evoxt advertises single-core clocks up to 6.0 GHz. Treat the number as the vendor's claim rather than a guarantee of your node; a fast single core does help compile jobs, small game servers and single-threaded Node apps, and the honest way to confirm it is to benchmark after deploy and before you commit to a year.

## The $2.99 plan is the most expensive RAM in the lineup

Price per gigabyte of RAM is the figure Evoxt's price list doesn't show, and it changes which plan is the sensible entry point:

- VM-0.5: $2.99 for 512 MB = **$5.98 per GB**
- VM-0.75: $4.99 for 1 GB = $4.99 per GB
- VM-1: $5.99 for 2 GB = **$3.00 per GB**
- VM-2, VM-4, VM-8 and VM-16 all land at $3.00 per GB as well.

The 512 MB plan costs twice as much per gigabyte as the 2 GB one, and for the same jump you also go from 5 GB of disk to 20 GB and from 250 GB of transfer to 500 GB. If your budget can stretch to $5.99, VM-1 is the better machine by a wide margin. VM-0.5 earns its place only when 512 MB is genuinely all the workload needs, which is true for a tunnel endpoint or a monitoring box and false for anything serving pages to people.

## What $2 to $3 does not buy

**A control panel.** A cPanel licence pushes a VPS into the $8–$10/month range at the cheap end, per HostAdvice's cPanel roundup, with premium cPanel boxes starting around $40. Evoxt's plan table lists no cPanel or Plesk licence, so budget for one separately if you need that interface. What you get instead is root access and a console, the normal arrangement at this price.

**Management.** At $2–$3 you are the sysadmin: OS patching, firewall rules, TLS renewal, and checking that backups actually restore. Evoxt's included weekly offsite backup removes one chore; it does not remove the rest.

**WordPress headroom.** HostAdvice puts 512 MB at the floor for WordPress with basic plugins and a cache layer. Floor means it boots and serves a trickle of traffic, not that it stays responsive under load. 👉 [Check what the $2.99 VM-0.5 includes before you decide](https://bit.ly/EvoXt)

## The real cost of annual billing

$24 a year is $2 a month, and $21.99 a year is $1.83 a month. That arithmetic is the whole trick behind most $2 VPS ads, and it is a fair one as long as you know what happens in month 13. Across the 37-host sample, the median sign-up price of $2.47/mo renews at a median $3.32/mo, about 34% more, though that renewal median only covers the 8 hosts that publish a renewal price. Only 4 of the 37 hold their price permanently.

Run two years on a $2.47 plan that renews at $3.32:

- Year 1: 12 × $2.47 = $29.64
- Year 2: 12 × $3.32 = $39.84
- Two years: $69.48, an average of $2.90/mo. Still under $3, but 17% above the number in the ad.

Ads quoting "$0.99/month" usually mean a three-year prepay. Divide the total you actually hand over by 36 before you compare it to anything.

Evoxt publishes monthly prices rather than a promotional first-term rate, and lets you prepay anywhere from one month to three years. Whatever a longer term does to the monthly figure at checkout applies to the term you paid for, so the number to write down is the amount due once that prepaid period ends. 👉 [Open Evoxt's plan list and confirm the billing term at checkout](https://bit.ly/EvoXt)

## Which plan fits which job

- **WireGuard or OpenVPN endpoint, uptime monitor, cron runner, chat bot:** VM-0.5 at $2.99. A 5 GB disk holds Debian plus the tunnel software, and 512 MB is enough for all four of those jobs at once.
- **Static site, small Node or Flask API, staging box:** VM-0.75 at $4.99. 1 GB stops you from tuning swap on day two.
- **WordPress with caching, a small LEMP stack, two or three Docker containers:** VM-1 at $5.99. 2 GB, 20 GB of disk and 500 GB of transfer is the first plan that doesn't feel tight.
- **App plus MySQL or Postgres on the same machine:** VM-1 at minimum; VM-1.5 at $6.95 if you want the second core for the database.
- **CI builds, game servers, compile-heavy work:** VM-2 at $11.99 or above. The high clock helps, 512 MB or 1 GB of RAM does not survive a real build.

## Who should not buy at this price

- **Anyone who needs cPanel or WHM to hand clients their own accounts.** That is the $8–$10/month bracket, and Evoxt's entry plans are not it.
- **Sustained CPU load.** These are shared vCPUs with no dedicated-core guarantee. A busy production service belongs on a larger plan or a dedicated box.
- **Anyone who wants managed support.** This is unmanaged hosting: the provider runs the hardware and the panel, you run the server.
- **Anyone who won't prepay and won't go above $3.** Evoxt's floor is $2.99 monthly with no annual trick to duck under $2.
- **Anyone who needs a written refund window before paying for a year.** Evoxt's pricing page doesn't publish a refund period, so ask support in writing before you prepay.

## Five things to check before checkout

1. **Billing term and the amount after it.** Note the recurring charge, not just the first invoice.
2. **Refund and cancellation terms**, in writing, especially on a 1–3 year prepay.
3. **Region and latency.** Pick the location nearest your users or yourself, and ping it before migrating anything.
4. **IPv4 included.** One IPv4 plus one IPv6 comes with every Evoxt plan; additional IPv4 addresses cost extra.
5. **Upgrade path.** Evoxt lets you add resources to an existing VM without changing plans, so starting small is reversible.

## FAQ

**Can a $2 VPS run WordPress?**
Yes, at 512 MB with a caching plugin and a short plugin list. 1 GB is the comfortable starting point and 2 GB is what you want if the site also runs WooCommerce or a page builder.

**Will the price go up after the first term?**
In the 37-host sample the median went from $2.47 to $3.32 at renewal, and only 4 hosts never raised prices. Evoxt lists monthly prices instead of a teaser first-term rate, so the figure in its table is the plan's monthly price; confirm the recurring amount on the invoice before you pay.

**Is cPanel included?**
No. A cPanel VPS starts around $8–$10/month at the budget end, which is roughly three times the price of Evoxt's smallest plan.

**Annual or monthly?**
Monthly if you're still testing what the box needs. Annual lowers the monthly equivalent but locks the money, so only prepay a term you'd be happy to keep if the workload changes.

**How much RAM do I actually need?**
512 MB for a single background service, 1 GB for a small site, 2 GB for an app with a database beside it, 4 GB and up once you're running containers or a panel.

## Pick by workload, then confirm two numbers

If the box exists to hold a tunnel, a bot or a monitor, VM-0.5 at $2.99 is the whole purchase. If it serves pages or runs an app with a database, go to VM-1 at $5.99 and skip VM-0.75, because $1 more buys twice the RAM, twice the disk and twice the transfer. And if you're prepaying more than a month, get the renewal amount and the refund terms confirmed in writing first.

👉 [Start from Evoxt's plan list and choose the size your workload needs](https://bit.ly/EvoXt)
