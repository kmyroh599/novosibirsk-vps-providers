# Novosibirsk VPS: Which Providers Really Have a Local Datacenter, What Entry Prices Cost After Add-Ons, and How to Choose a Plan (Full Plan Table)

Entry-level Novosibirsk VPS pricing starts at roughly 80 to 190 ₽/month, and at that price you get 512 MB to 1 GB of RAM on the smallest tier, not a box you'd put a real workload on. There's a second problem that costs people more time: most of the rankings that come up for this search recommend hosts whose servers sit in Moscow, Amsterdam or Almaty, not in Novosibirsk. Below you'll find which providers actually have hardware in the city, what the monthly bill looks like once IPv4 and DDoS add-ons land, what the cheapest tier quietly removes, and which JustHost plan matches which job.

> **Quick pick.** JustHost sells VPS in Russia with Moscow, Kazan and Novosibirsk locations, and you choose the datacenter at checkout. The cheapest plan worth running is **New Star at $3.81/mo** (1 core, 1 GB RAM, 10 GB NVMe, 100 Mbps fair-share port), or **$3.05/mo on a 12-month term**. The $1.99 VPS Promo is cheaper but caps the port at 10 Mbps, which is fine for a landing page or a monitoring node and painful for anything serving images.
> 👉 [See the New Star plan and select Novosibirsk at checkout](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)

## All JustHost VPS plans

JustHost runs a configurator: you start from a preset and change CPU, RAM, disk and port speed. The presets below are the NVMe line from the pricing page. The first price is the list rate; the second is what the 12-month term discount brings it to.

| Plan | vCPU / RAM / NVMe | Port (fair-share) | Price | Order |
| --- | --- | --- | --- | --- |
| VPS Promo | 1 / 512 MB / 5 GB | 10 Mbps (~4 TB/mo) | $1.99/mo | [ Order VPS Promo](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392) |
| New Star | 1 / 1 GB / 10 GB | 100 Mbps (~31 TB/mo) | $3.81/mo · $3.05/mo on 12 months | [ Order New Star](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392) |
| Double Star | 2 / 2 GB / 20 GB | 200 Mbps (~62 TB/mo) | $7.08/mo · $5.67/mo on 12 months | [ Order Double Star](https://justhost.asia/en/services/vps/tariffs/double-star-c2r2048nvme?ref=196392) |
| Bright Star | 4 / 4 GB / 30 GB | 300 Mbps (~93 TB/mo) | $9.80/mo · $7.84/mo on 12 months | [ Order Bright Star](https://justhost.asia/en/services/vps/tariffs/bright-star-c4r4096nvme?ref=196392) |
| Sirius | 1 / 1 GB / 20 GB | 300 Mbps (~93 TB/mo) | $4.85/mo · $3.88/mo on 12 months | [ Order Sirius](https://justhost.asia/en/services/vps/tariffs/sirius?ref=196392) |
| Arcturus | 1 / 2 GB / 30 GB | 300 Mbps (~93 TB/mo) | $6.92/mo · $5.53/mo on 12 months | [ Order Arcturus](https://justhost.asia/en/services/vps/tariffs/arcturus?ref=196392) |
| Alpha Centauri | 2 / 2 GB / 40 GB | 400 Mbps (~124 TB/mo) | $8.99/mo · $7.19/mo on 12 months | [ Order Alpha Centauri](https://justhost.asia/en/services/vps/tariffs/alpha_centauri?ref=196392) |
| Vega | 2 / 4 GB / 80 GB | 500 Mbps (~155 TB/mo) | $13.44/mo · $10.75/mo on 12 months | [ Order Vega](https://justhost.asia/en/services/vps/tariffs/vega?ref=196392) |
| Capella | 4 / 4 GB / 120 GB | 750 Mbps (~232 TB/mo) | $18.30/mo · $14.64/mo on 12 months | [ Order Capella](https://justhost.asia/en/services/vps/tariffs/capella?ref=196392) |

The list continues past Capella with Rigel (4 cores / 8 GB / 200 GB NVMe) and larger presets; those prices move with the configurator, so check them on the pricing page before ordering.

There's a second family of plans where you pick the storage type yourself, all with both an IPv4 and an IPv6 address, starting at $2.60/mo:

| Preset | HDD | SSD | NVMe |
| --- | --- | --- | --- |
| Start (1 core / 512 MB / 5 GB) | $3.25 → $2.60 | $3.90 → $3.12 | $4.22 → $3.38 |
| Standard (2 cores / 2 GB / 25 GB) | $11.00 → $8.80 | $13.20 → $10.56 | $14.30 → $11.44 |
| Super (4 cores / 4 GB / 50 GB) | $22.00 → $17.60 | $26.40 → $21.12 | $28.60 → $22.88 |

*Second figure = 20% off on the 12-month term.*

Two things the plan pages don't put in the same place. First, there is an IPv6-only line starting at **$1.60/mo**, which is a different product from the IPv4 + IPv6 line at $2.60 and up; if your site needs a Russian IPv4 address, the $1.60 entry doesn't get you one. Second, the VPS landing page currently shows a "special offers" block priced below the standard list: Sirius at $2.81/mo ($2.25 on 12 months), Arcturus at $4.01 ($3.21), Vega at $7.79 ($6.23), plus Yildun (4 cores / 8 GB / 200 GB) at $16.20, Betelgeuse (6 cores / 12 GB / 400 GB) at $26.40 and Altair (8 cores / 24 GB / 600 GB) at $47.40. Where the two pages disagree, the price at checkout is the one you pay.

👉 [Compare every JustHost VPS preset on one page](https://justhost.asia/en/services/vps/tariffs-all?ref=196392)

## Check the datacenter city before you compare prices

The Russian-language rankings that own this search term list ten hosts; six of them don't sell a Novosibirsk server at all. Here is where each one's hardware actually sits.

| Provider | Where the servers are | Entry price | Worth knowing |
| --- | --- | --- | --- |
| mnogoweb | Novosibirsk, ADMAN commercial DC, Tier 3 | from 190 ₽/mo | Xeon E5-2697v4 (2.3/3.6 GHz); one IPv4 included |
| deephost | Novosibirsk (NSK-01 to NSK-04), plus Moscow, St Petersburg, Kazan | 525 ₽/mo for 1 vCPU / 2 GB / 20 GB NVMe (page dated 2024) | outbound port 25 closed; Anti-DDoS billed separately |
| 4VPS.su | Novosibirsk | from 80 ₽/mo | KVM, NVMe, 1 IPv4 + /64 IPv6, trial up to 24 hours |
| Timeweb | Novosibirsk | from 150 ₽/mo | hourly billing; IPv4 charged as an extra |
| JustHost | Russia: Moscow, Kazan, Novosibirsk | $1.99/mo | Novosibirsk selected at checkout; configurator for CPU, RAM, disk, port |
| AdminVPS | Moscow, Tier III | from 299 ₽/mo | unlimited traffic, daily backups |
| Aeza | Moscow | Ryzen 9 9950X configs | unlimited traffic, Anti-DDoS up to 2 Tbps |
| FirstVDS | Moscow (WEB DC, IXcellerate), Netherlands (euNetworks), Almaty (Ahost.kz) | from 219 ₽/mo | 32 TB/mo on the main lines |
| Fornex | European datacenters | from about 600 ₽/mo | port capped at 100 Mbps |
| Beget | Russia, Kazakhstan, Europe | from 210 ₽/mo | SLA 99.98%, API/CLI/Terraform |
| ISHosting | 40+ countries, 44 cities | from about 600 ₽/mo | no Novosibirsk location listed |

That table is the whole argument for reading past the headline of a ranking. A host can be cheap, reliable and completely irrelevant to you if the packets you care about are leaving from Moscow. AdminVPS, Aeza, FirstVDS, Fornex, Beget and ISHosting all run solid infrastructure; none of them puts a server in Novosibirsk.

One more trap in this niche: a site that looks like a local Novosibirsk host but hasn't been touched in years. vps54.ru lists three plans in a Novosibirsk datacenter, all OpenVZ, all 32-bit only (CentOS 5, Fedora, Debian), with no prices displayed and a 2017 copyright in the footer. OpenVZ with a 32-bit CentOS 5 is not something to launch a project on in 2026, and the missing price tells you nobody is maintaining the page.

On availability figures: mnogoweb publishes a 99.9% guarantee and, on the same page, cites a third-party monitor reporting 100%. Those are two different measurements, so don't read them as one number.

## A 190 ₽ plan is rarely a 190 ₽ bill

Headline prices in this market exclude things you probably need.

**Timeweb** starts at 150 ₽/mo, then charges IPv4 as an extra at 150 ₽/mo (IPv6 is free), sells DDoS protection at 450 ₽/mo, and bills automatic backups at 6 ₽/GB. Add the address and the protection and a 150 ₽ server becomes 750 ₽/month before you've stored a single backup.

**mnogoweb** includes one IPv4 address in the plan, which makes its 190 ₽ more comparable than it first looks. Additional addresses cost 160 ₽/month each, up to 16, and an extra /112 IPv6 network is 50 ₽.

**deephost** quotes 525 ₽ for the smallest Novosibirsk box, with Anti-DDoS StormWall connected separately after you contact support. The number on the card is the number without protection.

With JustHost, the thing to watch is the address family rather than a stack of add-ons: the IPv6-only entry at $1.60 and the IPv4 + IPv6 line at $2.60 are separate products, and the NVMe presets are quoted with a fair-share port rather than a dedicated uplink. Compare like with like before you declare one host cheaper than another.

## What the cheap tier actually removes

mnogoweb is unusually explicit about this, and the pattern applies across the market. Its budget line caps the network at 50 Mbps, caps disk throughput at 50 MB/s and ships without managed administration. The standard line gives you up to 250 Mbps, SSD at up to 500 MB/s or NVMe at up to 7,000 MB/s, and five support tickets a month plus unlimited consultations.

The same page admits something the rankings never mention: the advertised port speed isn't guaranteed, because the physical host's 1 Gbps uplink is shared across all the virtual servers on it. If you need sustained bandwidth, you're supposed to ask before ordering.

That's the right lens for JustHost's cheapest preset too. VPS Promo gives you 1 core, 512 MB and 5 GB of NVMe behind a 10 Mbps fair-share port. For a single landing page, a DNS node, a wireguard endpoint or an uptime checker, that's genuinely enough and you save $1.82 a month against New Star. For anything that pulls Docker images, rsyncs backups or serves uncached images, the 100 Mbps port on New Star pays for itself the first afternoon.

👉 [Order the $1.99 VPS Promo if 10 Mbps is all you need](https://justhost.asia/en/services/vps/tariffs/promo-c1r512nvme?ref=196392)

## If you need to send email, read this before you order

deephost states plainly that outbound port 25 is closed in its Novosibirsk datacenter, for security and IP-reputation reasons. That single line disqualifies the cheapest local option for anyone running a mail server, a CRM's SMTP relay or cold outreach. mnogoweb's feature table has a dedicated row for "ability to open SMTP ports", which tells you it varies by plan line there as well.

If outbound mail is part of the job, options exist but the terms are strict. cuberdp sells KVM VPS with port 25 open by default from $2.15/mo (1 vCPU, 1 GB RAM, 5 GB NVMe, 50 Mbit/s), with IP changes at $1.00 each, PTR/rDNS set up via a ticket, and delivered servers generally non-refundable. Its acceptable-use page permits Mailwizz, Postal and Mautic but bans unlicensed bulk sending, and repeated complaints get the server suspended. Note also that its cheap Russian location is Kemerovo, not Novosibirsk.

JustHost's plan pages don't state a port-25 policy either way, so ask support before you buy if outbound mail matters to you.

## Which plan fits which job

- **One Russian IP for a landing page, geo-check or small static site:** VPS Promo at $1.99/mo, or Start on the storage-selectable line if you want to choose HDD, SSD or NVMe.
- **A control panel and a database, a handful of sites:** 2 GB of RAM and NVMe. Arcturus gives you 1 core, 2 GB and 30 GB for $6.92/mo; Double Star gives you a second core with 20 GB for $7.08/mo. Take Arcturus if disk matters more, Double Star if compile times do.
- **Docker builds, multiple containers, image-heavy sites:** Vega at 2 cores / 4 GB / 80 GB for $13.44/mo is the first plan where the disk and RAM stop being the constraint.
- **You need to send mail:** confirm port 25 in writing before paying.
- **DDoS is a real risk for you:** add the protection cost to the plan price before comparing anything, because it changes the ranking.

Five things to confirm at checkout, in this order: the datacenter city (Novosibirsk, not just "Russia"), the billing term behind the discount, whether an IPv4 address is included, whether the port is dedicated or fair-share, and the refund terms for annual payments.

👉 [Start with New Star at $3.05/mo on the 12-month term](https://justhost.asia/en/services/vps/tariffs/new-star-c1r1024nvme?ref=196392)

## FAQ

**Does a Novosibirsk datacenter actually reduce latency for Siberian users?**
Physically hosting in Novosibirsk means traffic to users in Novosibirsk, Omsk, Krasnoyarsk and nearby regions doesn't have to route through Moscow first, which is the point of paying for a local node. No provider in this market publishes latency figures per city, so test from your own users' networks before you commit to an annual term.

**Can I pay with a non-Russian card?**
Russian hosts in this segment list Russian bank cards, Belkart, SBP, Юmoney and ruble bank transfers; whether a foreign card works isn't stated on their pages, so assume you'll need a Russian payment method until support tells you otherwise. JustHost.asia, the international storefront, is reported in an April 2026 third-party review to accept Alipay and WeChat Pay, which makes it the easier option if you're paying from outside Russia. Confirm the current payment list at checkout.

**KVM or OpenVZ?**
KVM for anything new. OpenVZ pages like vps54.ru's are frozen in the 32-bit CentOS 5 era, and even leaving the age aside, KVM gives you a real kernel, custom ISO installation and no noisy-neighbour memory games. Every JustHost preset here is KVM.

**Can I add extra IPv4 addresses?**
mnogoweb sells up to 16 extra addresses at 160 ₽/month each, with the first one free. JustHost's plan pages don't publish an extra-IP price list, so ask support if you need more than the address that comes with the plan.

**Is the port speed guaranteed?**
On fair-share plans, no. mnogoweb says outright that the advertised maximum isn't guaranteed because the host's 1 Gbps uplink is shared, and JustHost labels its ports "unmetered (fair-share)" with a monthly traffic equivalent. If you need a committed rate, that's a question for sales, not a line item on the plan card.
