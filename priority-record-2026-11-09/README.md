# An early independent proposal for prosumer distributed AI compute — documented publicly since 11 Oct 2025

Author: Slava Solodkiy (Vladislav Solodkiy) · Record compiled: 9 Nov 2026 with AI assistance (Claude), reviewed by the author after publication · Repository: slavasolodkiy/datacenters-AI

This page is an append-only dated record. It does not edit, replace or re-date any earlier release in this repository. It makes no claim to be the first inventor of anything and no patent claim.

## 1. What the proposal was

A "share-to-earn" network for prosumer AI hardware: owners of AI mini-PCs and workstations connect idle capacity to a marketplace that runs real AI workloads (not crypto mining), described at the time as an "Airbnb for AI compute" under the working name Nebius NextDoor.

## 2. Dated primary public sources

| Date (UTC) | Source | What it shows | How the date is verified |
|---|---|---|---|
| 11 Oct 2025, 19:51 | GitHub release [v12.10.2025](https://github.com/slavasolodkiy/datacenters-AI/releases/tag/v12.10.2025) — "The Decentralized AI Nextdoor-Compute Market: 'Airbnb for AI'" | DePIN analysis of aggregating underused GPUs, including consumer-grade hardware, plus a whitepaper draft "Nebius NextDoor: The Decentralized AI Compute Revolution" | GitHub release timestamp; the repository's commit 47cd59b shows GitHub signature status "verified" (checked 9 Nov 2026) |
| 11 Oct 2025, 17:16 | GitHub release [v11.10.2025](https://github.com/slavasolodkiy/datacenters-AI/releases/tag/v11.10.2025) — "Comparative Analysis of Five AI Computers" | Hardware side of the same proposal | GitHub release timestamp |
| 8 Nov 2025, 14:45 | [X post @SlavaSolodkiy](https://x.com/SlavaSolodkiy/status/1987169568691785790) | Public launch post for Nebius NextDoor | Time decoded from the post ID |
| 11 Nov 2025, 10:10 | GitHub release [v.11.11.2025](https://github.com/slavasolodkiy/datacenters-AI/releases/tag/v.11.11.2025) — "Nebius Olares (Nothing Centralized Edition)" | Follow-up concept: an AI mini-station bundle with membership in a "share-to-earn" decentralized compute network. An author concept bundle, not a product or partnership of any hardware vendor | GitHub release timestamp |
| June 2026 | Book companion site [thrillion.eu](https://thrillion.eu/) (Labs, IDEA 07) | "Sell prosumer AI PCs on credit, pre-integrated with DePIN so they earn from day one", explicitly fenced as "a 2028–2030 concept in a 2026 reality" | "June 2026" as printed on the page; no machine-readable date verified |

## 3. How later public developments compare (bounded)

Each comparison says only what the public source says. None of these organisations is connected to this proposal.

| Date | Development | Overlap | Difference |
|---|---|---|---|
| 30 Apr 2025 filed · 5 Nov 2026 published | Microsoft US patent application US 2026/0349820 A1 ("Opportunistic Micro-training on Edge Devices Using Spare GPU Utilization"), as reported | Spare consumer GPU capacity, owners compensated | Filed before this proposal's public date. A published application is not a granted patent and not a launched service. Not independently re-verified for this record — see [card 04](signal-cards/04-microsoft-published-application.md) |
| 20 Jul 2026 | [Together AI × Y Combinator dedicated GPU cluster](https://www.together.ai/blog/together-yc-gpu-cluster) | Shared compute for a community of startups | One centrally provisioned cluster, not a federation of owner devices |
| 1 Oct 2026 | [Starlink Community Host programme](https://teslanorth.com/2026/10/01/starlink-community-host-program-passes/) | An owner shares a device's capacity with neighbours and earns monthly income; the platform handles payments | Connectivity, not compute — see [card 01](signal-cards/01-starlink-community-host.md) |
| Oct 2026 | Apple Machine Learning Research: ["Minions: A Dynamic and Distributed Virtual GPU Cloud Built on Idle Apple Silicon Devices"](https://pr-mlr-shield-prod.apple.com/research/distributed-gpu-cloud) ([arXiv:2610.12970](https://arxiv.org/abs/2610.12970), 9 Oct 2026) | Idle personal devices pooled for AI inference | Research publication, not a commercial product — see [card 02](signal-cards/02-apple-minions-research.md) |
| 20 Oct 2026 | Google Cloud London (europe-west2) outage disrupting Revolut and other UK services ([UptimeRobot](https://uptimerobot.com/knowledge-hub/reports-research/google-cloud-london-outage-revolut/), [Irish News](https://www.irishnews.com/news/uk/revolut-services-down-as-google-cloud-apologises-for-outage-XCDIUTFFRVMY3GEVX5LIBV2NNA/)) | Concentration risk of centralized cloud | Local compute cannot replace a bank's core systems — see [card 03](signal-cards/03-google-cloud-outage-local-failover.md) |

## 4. What this record does not claim

- Not "first": Microsoft's application was filed on 30 Apr 2025, before 11 Oct 2025. The accurate wording is "independently and publicly documented since 11 Oct 2025".
- No earnings or return-on-investment promise for any device owner.
- No partnership, endorsement or approval by any company named on this page.
- Signatures: the commit adding this record (4c29569) was signed with an SSH key by the AI-assisted session that pushed it (Claude, noreply@anthropic.com); GitHub shows it as "Verified" for that identity. It is not signed with the author's own GPG key. The original commit 47cd59b is the author's signed commit.

## 5. Contents of this release

- `README.md` — this page
- `signal-cards/01-starlink-community-host.md`
- `signal-cards/02-apple-minions-research.md`
- `signal-cards/03-google-cloud-outage-local-failover.md`
- `signal-cards/04-microsoft-published-application.md`
