# Zuno Network — Litepaper v1.0

Improved AI Accuracy, Powered by Humans and Decentralized Compute

---

## Table of Contents

1. [Introduction](#1-introduction)
2. [How it Works](#2-how-it-works)
3. [Validator Nodes](#3-validator-nodes)
   - [3.1 Overview](#31-overview)
   - [3.2 Role of Validator Nodes](#32-role-of-validator-nodes)
   - [3.3 Node Requirements](#33-node-requirements)
   - [3.4 Rewards](#34-rewards)
   - [3.5 Phased Rollout](#35-phased-rollout)
4. [Tokenomics](#4-tokenomics)
5. [Funding & Development](#5--funding--development)
6. [Reward Emissions](#6-reward-emissions)
   - [6.1 Overview](#61-overview)
   - [6.2 Reward Types](#62-reward-types)
   - [6.3 Emission Structure](#63-emission-structure)
   - [6.4 Distribution Flow](#64-distribution-flow)
   - [6.5 Sustainability](#65-sustainability)
7. [Pre‑Mine](#7-premine)
   - [7.1 Purpose](#71-purpose)
   - [7.2 Points System](#72-points-system)
   - [7.3 Wallet Linking Requirement](#73-wallet-linking-requirement)
   - [7.4 Snapshot Date](#74-snapshot-date)
   - [7.5 Airdrop](#75-airdrop)
   - [7.6 Supply at Launch](#76-supply-at-launch)
   - [7.7 Transition to Public Trading](#77-transition-to-public-trading)
8. [Launch Plan](#8-launch-plan)
   - [8.1 Overview](#81-overview)
   - [8.2 Phase 0 — Private Beta Testing](#82-phase-0--private-beta-testing)
   - [8.3 Phase 1 — Pre‑Mine](#83-phase-1--pre-mine)
   - [8.4 Phase 2 — Community Growth](#84-phase-2--community-growth)
   - [8.5 Phase 3 — Liquidity Launch](#85-phase-3--liquidity-launch)
   - [8.6 Phase 4 — Token Goes Live](#86-phase-4--token-goes-live)
   - [8.7 Phase 5 — Post Launch Growth](#87-phase-5--post-launch-growth)
   - [8.8 Phase 6 — Enterprise & Governance](#88-phase-6--enterprise--governance)
   - [8.9 Phase 7 — AI Infrastructure](#89-phase-7--ai-infrastructure)
   - [8.10 Phase 8 — Zuno AI](#810-phase-8--zuno-ai)
9. [Roadmap](#9-roadmap)
10. [Security & Transparency](#10-security--transparency)
    - [10.1 Security Principles](#101-security-principles)
    - [10.2 Contributor Security](#102-contributor-security)
    - [10.3 Data Integrity & Consensus](#103-data-integrity--consensus)
    - [10.4 Transparency Commitments](#104-transparency-commitments)
    - [10.5 No Insider Advantage](#105-no-insider-advantage)
    - [10.6 Continuous Monitoring](#106-continuous-monitoring)
11. [Governance](#11-governance)
    - [11.1 Overview](#111-overview)
    - [11.2 What Token Holders Vote On](#112-what-token-holders-vote-on)
    - [11.3 How Voting Works](#113-how-voting-works)
    - [11.4 Voting Phases](#114-voting-phases)
    - [11.5 Governance Principles](#115-governance-principles)
12. [About the Founder](#12-about-the-founder)
13. [Conclusion](#13-conclusion)

---

## 1. Introduction

**The Problem:** AI is a powerful tool — but it still makes mistakes.

AI hallucinations produce incorrect answers with confidence, creating real‑world risk for businesses, governments, and users who need accuracy.


**The Solution:** Zuno Network

Zuno Network uses a smartphone app (Android and iOS) 
that turns everyday people into AI trainers. By reviewing 
AI-generated answers — a process the industry calls 
**data labeling** — contributors help improve AI accuracy 
and earn **Zuno tokens** on the Solana blockchain as a 
reward for every task completed.

To ensure the quality and integrity of that data, contributor submissions are reviewed by a decentralised network of **Validator Nodes** — independent operators who verify responses, reach consensus, and earn ZUNO rewards for accurate participation.

No experience needed. No cost to join. 
Anyone in the world can contribute and earn.

*Zuno tokens are earned as rewards for completing tasks 
and are not offered as a financial investment.*

---

## 2. How it Works

### 1. Distributing the Data
Zuno Network breaks down complex AI training tasks into small, manageable pieces. These tasks are sent to the Zuno Android/iOS App so people can complete them from anywhere.

### 2. AI Data Labelling
People using the Zuno app receive a question alongside two AI-generated answers and select the most accurate one — a process known as **AI data labelling**. This method, formally called **Reinforcement Learning from Human Feedback (RLHF)**, is the industry standard for improving AI quality through human input.

### 3. Validator Nodes
Once contributors submit their answers, a decentralised network of Validator Nodes reviews the responses. Validators score answer quality, flag suspicious submissions, and reach consensus on the correct result — ensuring only verified, high-quality data enters the training dataset. Validators earn ZUNO rewards for accurate participation, on the same terms as contributors.

### 4. Solana‑Powered Rewards
For every task completed — whether as a contributor or a Validator Node operator — you earn Zuno tokens on the Solana blockchain. Solana ensures rewards are fast, transparent, and easy to claim.

### 5. Improved AI Accuracy Through Human Data Labelling
Your input helps create higher‑quality training data. Over time, this builds more accurate AI models — verified by real people, not controlled by a single company.

---

## 3. Validator Nodes

### 3.1 Overview

As the Zuno Network scales, the volume of AI data labelling task responses submitted by Zuno App contributors grows significantly. To maintain data quality, prevent fraud, and establish trustworthy consensus over what constitutes a correct AI data labelling answer, Zuno will introduce a dedicated Validator Node layer.

Validator Nodes are a network of decentralised node operators who run software that reviews batches of contributor task responses, scores their quality, flags suspicious submissions, and submits verdicts to the Zuno consensus engine. Validators earn ZUNO rewards for accurate, honest participation and face stake slashing for persistent outlier behaviour.

---

### 3.2 Role of Validator Nodes

Each Validator Node receives a task bundle — a question ID together with all responses submitted for that question by contributors. The validator independently scores each response and submits a verdict before seeing the verdicts of any other validator. The consensus engine then weighs all verdicts together to determine the accepted answer.

Validators serve three core functions within the network:

* **Accuracy scoring** — evaluating whether submitted task responses are factually correct and of sufficient quality to enter the training dataset.
* **Fraud detection** — identifying bot-driven, duplicate, or otherwise suspicious submissions before they corrupt the dataset.
* **Consensus participation** — contributing to a distributed agreement mechanism that removes any single point of control over what gets labelled "correct."

---

### 3.3 Node Requirements

To operate a Validator Node, participants must:

* Stake a minimum ZUNO amount to the network — this acts as economic collateral and aligns validator incentives with honest participation.
* Maintain a minimum uptime threshold, consistent with network reliability standards.
* Pass an initial benchmarking round using known-answer tasks before going live. Nodes that fail benchmarking are not assigned live tasks until accuracy thresholds are met.

**Task assignment:** Rather than all validators reviewing every task, Zuno pseudorandomly assigns a subset of validators (target: 5–9 nodes) per task bundle, weighted by stake size and reputation score. This ensures the system scales with task volume without bottlenecks.

---

### 3.4 Rewards

Validator Node rewards are drawn from the Community Treasury alongside contributor task rewards. Validators earn at a higher per-task rate than contributors to compensate for the capital lockup required by staking.

Validator rewards follow the same principles as all other Zuno emissions:

* Rewards are earned through verifiable work — consensus participation, uptime, and accuracy.
* No rewards are issued for passive staking alone.
* Loyalty-based contribution bonuses apply to validators who maintain consistent participation over time, on the same terms as contributors.

---

### 3.5 Phased Rollout

Validator Nodes are introduced at Phase 0 and Phase 1 alongside Zuno App contributors. During the pre-mine period, Validator Node operators earn points for each task bundle reviewed, on the same 1:1 conversion terms as contributors — 1 point converts to 1 ZUNO token at the Token Generation Event (TGE).

**Phase 1 validator platforms:**
* Android smartphones
* Windows (Docker)
* Linux (Docker)

---

## 4. Tokenomics

### 4.1 Token Allocation

**Total Supply: 1,000,000,000 ZUNO**

| Category | % | Tokens | Vesting | Notes |
|---|---|---|---|---|
| **Community Treasury** | **55%** | 550,000,000 | Contributor task rewards and Validator Node operator rewards |
| **Founder & Team** | **15%** | 150,000,000 | 3 year vest, 12 month cliff | Core development team |
| **Investors & Grants** | **15%** | 150,000,000 | 2 year vest, 6 month cliff | VC rounds, foundation grants |
| **Ecosystem & Partnerships** | **8%** | 80,000,000 | Milestone-based release | Integrations, enterprise onboarding |
| **Exchange Liquidity** | **5%** | 50,000,000 | Locked 24 months at launch | Required for public trading |
| **Operations & Infrastructure** | **2%** | 20,000,000 | Quarterly release | AI hosting and inference costs |

**Total: 100%**

---

### Community Treasury — 55%

The largest allocation is reserved for the people who build the network. Community Treasury tokens are distributed exclusively as task rewards to contributors who complete AI data labelling work inside the Zuno app. No tokens from this allocation are distributed to the team, investors, or any third party. Emission follows a four-year declining schedule, with reward rates recalibrated periodically by governance to reflect network growth and task volume.

---

### Founder & Team — 15%

A portion of the supply is allocated to the founding team and future core hires who build and maintain the Zuno protocol. All team tokens are subject to a twelve-month cliff followed by a twenty-four month linear vest, for a total vesting period of three years. No team tokens enter circulation before the cliff expires. This structure aligns the founding team's incentives with the long-term health of the network.

---

### Investors & Grants — 15%

This allocation is reserved for strategic capital that supports Zuno's development and growth. It covers venture capital funding, ecosystem grants from foundation programs such as the Solana Foundation, and any future strategic investment rounds. Investor tokens are subject to a six-month cliff followed by an eighteen-month linear vest. Grant allocations are released on a milestone basis as agreed with the relevant foundation or program. All funding events of material significance will be disclosed publicly.

---

### Ecosystem & Partnerships — 8%

Reserved for integrations, enterprise onboarding, and strategic partnerships that expand the reach and utility of the Zuno network. Tokens from this allocation are released on a milestone basis rather than a fixed schedule, ensuring they are deployed only in exchange for measurable network value. This includes partnerships with AI companies, data buyers, and infrastructure providers.

---

### Exchange Liquidity — 5%

A dedicated allocation backs the initial Zuno liquidity pool on Raydium at the time of public trading launch. These tokens are paired with SOL and locked for twenty-four months from the date of deployment, providing stable on-chain liquidity throughout the network's critical early growth phase. The liquidity deployment transaction and lock expiry will be published on-chain and verifiable publicly.

---

### Operations & Infrastructure — 2%

A small operational reserve covers the direct costs of running the Zuno network during its early stages, including AI model hosting, inference infrastructure, and network maintenance. This allocation is released on a quarterly basis and subject to public reporting. As the network matures, operational costs are expected to be covered by data revenue rather than token allocation.

---

## Vesting Philosophy

Zuno's vesting structure is designed around a single principle: tokens should be earned, not extracted. Every allocation — whether team, investor, or ecosystem — carries a lock-up period that extends well beyond the public trading launch. This ensures that no single party can create short-term selling pressure at the expense of the network's contributors and long-term participants.

| Allocation | Cliff | Vest | Total Lock-up |
|---|---|---|---|
| Community Treasury | None | 4 years, declining emissions | 4 years |
| Founder & Team | 12 months | 24 months linear | 3 years |
| Investors & Grants | 6 months | 18 months linear | 2 years |
| Ecosystem & Partnerships | None | Milestone-based | Variable |
| Exchange Liquidity | None | Locked 24 months | 2 years |
| Operations & Infrastructure | None | Quarterly | Ongoing |


---

### 4.2 Long-Term Sustainability

Zuno's economic model is designed for durability, grounding token value in real-world demand rather than speculation.

**Revenue model**

Enterprises and AI developers pay to access Zuno's human-verified datasets — labelled, rated, and validated by real contributors completing tasks in the app. As demand for high-quality AI training data grows, so does the utility and throughput of the Zuno network.

**Fee structure**

A portion of enterprise data access fees flows back into the network treasury. These funds support:

- Ongoing protocol development and infrastructure costs
- Contributor reward supplementation during early growth phases
- Governance-approved ecosystem initiatives

**Token emission and governance**

ZUNO token holders participate in governance over key network parameters, including emission rates, reward weightings, and treasury deployment. As the network matures, governance transitions from founder-led to fully community-driven, ensuring long-term alignment between contributors, partners, and token holders.


---

## 5.  Funding & Development

Zuno Network is currently self-funded through the founding team. To support continued development and network growth, Zuno is actively exploring:

Grants from ecosystem foundations and Web3 infrastructure programs
Venture capital from crypto-native investors aligned with decentralised AI and data infrastructure
Strategic partnerships with organisations that benefit from Zuno's data labelling network

Funding will be used to support core development, liquidity, and network expansion. Any material funding events will be disclosed publicly in line with Zuno's commitment to transparency.


---

## 6. Reward Emissions

### 6.1 Overview
All ZUNO rewards come from the Community Treasury. Rewards are earned 
through real participation — completing AI data labelling tasks and 
long‑term contribution to the network.

No staking. No lockups. No guaranteed returns.

### 6.2 Reward Types

**1. Task Rewards**
Earned for completing AI data labelling tasks:
- Reviewing AI-generated answers
- Selecting the most accurate response
- Correcting AI mistakes

Rewards scale with task volume and difficulty.

**Task Reward Rate**

| Phase | Reward per Task | Daily Maximum | Notes |
|---|---|---|---|
| Pre‑mine | 1 point | 10 points/day | Points tracked in Zuno backend, not on‑chain |
| Launch | 1 ZUNO | 10 ZUNO/day | Tokens distributed from Community Treasury |

- Points convert to ZUNO at a 1:1 ratio at launch
- Rewards are earned through completed tasks only
- No rewards are given for holding, staking, or purchasing tokens

**2. Long‑Term Contribution Rewards**
Contributors who remain consistently active over longer periods 
receive periodic bonus multipliers on task rewards. These bonuses 
are based purely on participation activity and do not involve 
staking, lockups, or passive holding.


### 6.3 Emission Structure

ZUNO uses a task‑based emission model:
- Rewards are issued per completed task
- Emissions scale with real usage
- No fixed daily or block emissions
- No inflation

This extends the lifespan of the treasury and prevents over‑emission.

### 6.4 Distribution Flow
1. A task is completed.  
2. The system assigns a reward amount.  
3. Loyalty multipliers apply if the contributor has a long activity streak.  
4. Tokens are released from the Community Treasury.  
5. The contributor claims them on‑chain.

### 6.5 Sustainability
The model is designed to:
- Reward early contributors  
- Scale with network demand  
- Avoid draining the treasury during quiet periods  
- Support multi‑year emissions


---

## 7. Pre‑Mine

### 7.1 Purpose
The pre‑mine phase builds Zuno's initial contributor base before 
trading opens. Contributors earn **points** during this phase by 
completing AI data labelling tasks in the Zuno app. Points are 
tracked in the Zuno backend dashboard and are not on‑chain.

### 7.2 Points System
During the pre‑mine, all task contributions are recorded as points:

- **1 task completed = 1 point**
- **Maximum 10 points per day per contributor**
- Points are not on‑chain and no ZUNO tokens are distributed 
  during this phase

### 7.3 Wallet Linking Requirement
To be eligible for the airdrop, contributors must link a valid 
Solana‑compatible wallet in the Zuno app before the snapshot date. 
The snapshot date is the deadline after which no new wallets can 
be linked for airdrop eligibility. Contributors who do not link 
a wallet before this date will not receive the airdrop.

### 7.4 Snapshot Date
The snapshot date is the fixed date exactly 30 days after the Zuno 
app goes live. On this date, the Zuno backend records every 
contributor's final point balance. This frozen balance becomes their 
ZUNO token allocation for the airdrop. No points earned after the 
snapshot date count toward the initial airdrop. Contributors must 
have linked a valid Solana‑compatible wallet in the Zuno app before 
the snapshot date to be eligible to receive tokens.

### 7.5 Airdrop
After the snapshot date, ZUNO tokens are distributed to all eligible 
wallets at a 1:1 ratio — **1 point = 1 ZUNO token.**

- Only contributors with a linked wallet before the snapshot date 
  are eligible
- Tokens are distributed from the Community Treasury
- No tokens are sold, presold, or privately allocated
- All tokens in the initial circulating supply are earned through 
  real task contribution


### 7.6 Supply at Launch
Only ZUNO distributed via the launch airdrop becomes the initial 
circulating supply. Every token in circulation is earned through 
real contribution — completing AI data labelling tasks in the Zuno app.

Everyone enters at the same starting price when liquidity goes live.

### 7.7 Transition to Public Trading
Once the launch airdrop is complete, the initial Raydium liquidity 
pool is deployed:

- 1,000,000 ZUNO
- $1,000–$10,000 SOL
- Target price: ~$0.001

After this point:
- ZUNO becomes tradable
- Contributors continue earning normally

---

## 8. Launch Plan

### 8.1 Overview
Zuno launches through a staged, transparent rollout designed for 
fairness, stability, and real network participation. Every token 
in circulation is earned through real contribution — not purchased, 
allocated, or reserved in advance.

---

### 8.2 Phase 0 — Private Beta Testing

- Zuno app tested privately with a small group
- Contributor workflow validated end‑to‑end
- AI data labelling tasks tested for accuracy, stability, and 
  consistent formatting
- API load, latency, and error handling monitored
- Loyalty multiplier logic tested
- UI/UX refined based on tester feedback
- No emissions, no rewards, no token activity

**Purpose:** Ensure the contributor experience and task pipeline 
are stable before the pre‑mine begins.

---

### 8.3 Phase 1 — Pre‑Mine (Zuno Points Earning Period)

- Contributors download the Zuno app
- Complete AI data labelling tasks and earn **points** (not ZUNO tokens)
- 1 task completed = 1 point, maximum 10 points per day per contributor
- Points are tracked in the Zuno backend dashboard — no on‑chain 
  activity during this phase
- Loyalty multipliers reward consistent participation
- Contributors must link a Solana‑compatible wallet in the Zuno app 
  before the snapshot date to be eligible for the airdrop
- No trading, no liquidity, no token sales

**Snapshot Date:** Exactly 30 days after the Zuno app goes live, 
the backend records every contributor's final point balance. This 
frozen balance determines their ZUNO allocation.

**Airdrop:** After the snapshot, ZUNO tokens are distributed to all 
eligible wallets at 1 point = 1 ZUNO. Only contributors who linked 
a valid Solana‑compatible wallet before the snapshot date receive 
the airdrop.

**Purpose:** Build a real contributor base and create an earned 
initial circulating supply through real task contribution.

---

### 8.4 Phase 2 — Community Growth

- Contributor count grows throughout the pre‑mine period
- Task throughput increases
- Emissions scale with real activity
- App stability improves across devices
- Community forms around real participation
- Transparency dashboards activated

**Purpose:** Reach a healthy contributor base before liquidity deployment.

---

### 8.5 Phase 3 — Liquidity Launch

- Deploy Raydium liquidity pool
- Pair **1,000,000 ZUNO** with **$1,000–$10,000 SOL**
- Target starting price: **~$0.001**
- LP tokens locked for 24 months

**Purpose:** Establish a fair, stable entry price.

---

### 8.6 Phase 4 — Token Goes Live

- ZUNO becomes tradable
- Pre‑mine tokens enter circulation via the launch airdrop
- Everyone enters at the same starting price
- On‑chain ZUNO reward claiming activated
- Governance framework introduced
- Public enterprise API access opens

**Purpose:** Enable open market discovery and transition to full 
on‑chain operations.

---

### 8.7 Phase 5 — Post Launch Growth

- Expanding contributor base
- Increasing task throughput
- Stabilising emissions
- Growing liquidity depth
- Publishing transparency dashboards (tasks, emissions, treasury)
- Dataset quality scoring and audit tools

**Purpose:** Demonstrate real usage and real contributors post-launch.

---

### 8.8 Phase 6 — Enterprise & Governance

- Public enterprise API access matures
- Dataset licensing and enterprise‑grade API tiers introduced
- Zuno SDK for developers released
- Enterprise integrations for AI accuracy services
- On‑chain governance voting activated via smart contracts
- Community proposals and votes executed automatically

**Purpose:** Build Zuno's commercial layer and hand governance 
fully to the community.

---

### 8.9 Phase 7 — AI Infrastructure Roadmap

- Hybrid sovereign cloud architecture  
- Dedicated Zuno inference clusters  
- High-volume enterprise AI workloads  
- Model-agnostic compute layer for open-source LLMs  
- Zuno Federated AI Infrastructure  
- Geo-distributed sovereign AI infrastructure with regional encrypted GPU clusters for low-latency private inference and RAG workloads  
- Federated AI compute mesh with city-based encrypted GPU nodes orchestrated into scalable low-latency AI edge clusters  

**Purpose:** Build scalable AI infrastructure powered by community-validated data, optimized for secure enterprise AI, private inference, and future sovereign AI workloads.

---

### 8.10 Phase 8 — Zuno AI

- Zuno's own AI model trained on community‑verified datasets
- Fine‑tuning via open‑source model families
- Accuracy‑first architecture
- Integrated into Zuno's enterprise products

**Purpose:** Deliver a high‑accuracy AI model built entirely on 
community‑validated data.


---

## 9. Roadmap

The table below provides a high‑level summary of the Zuno Network 
phase sequence. Full detail for each phase is in Section 8 — Launch Plan.

| Phase | Name | Key Milestone |
|---|---|---|
| Phase 0 | Private Beta Testing | App and API validated internally |
| Phase 1 | Pre‑Mine | Points earned, snapshot taken, airdrop distributed |
| Phase 2 | Community Growth | Contributor base expands, task throughput scales |
| Phase 3 | Liquidity Launch | Raydium pool deployed, LP locked for 24 months |
| Phase 4 | Token Goes Live | ZUNO tradable, on‑chain rewards, governance introduced |
| Phase 5 | Post Launch Growth | Network stabilised, dashboards live, liquidity deepens |
| Phase 6 | Enterprise & Governance | Enterprise API, SDK, on‑chain governance |
| Phase 7 | AI Infrastructure | Federated sovereign AI infrastructure, encrypted regional GPU clusters, enterprise inference and RAG workloads |
| Phase 8 | Zuno AI | Community‑trained AI model released |


---

## 10. Security & Transparency

### 10.1 Security Principles
Zuno is designed around three core security principles:

- Every client must be authenticated
- Every task must be verifiable
- Every reward must be earned through measurable work

### 10.2 Contributor Security
The Zuno app uses a lightweight but strict security model:

- Per‑session authentication ensures each contributor session is unique
- Task integrity checks verify that AI data labelling tasks are 
  delivered exactly as issued
- Anti‑automation protections prevent scripted or bot‑driven submissions
- Server‑side validation confirms each task response matches a valid 
  task ID and timestamp

All contributions are logged, rate‑limited, and verified before 
rewards are issued.

### 10.3 Data Integrity & Consensus
Zuno uses a multi‑layer validation model:

- Contributors confirm the accuracy of AI data labelling tasks
- Consensus scoring compares responses across multiple contributors
- Disagreements trigger review and may reduce rewards for outlier responses
- All decisions are logged for auditability

This ensures human‑validated data remains trustworthy.


### 10.4 Transparency Commitments
Zuno is built to be verifiable from day one.

**Public Dashboards**
The network publishes:
- Active contributors
- Tasks completed per day
- Emissions per role
- Treasury balance and outflows
- Consensus accuracy metrics

**Open Reward Logic**
Reward formulas are public, deterministic, and tied directly to:
- Validated tasks
- Consensus agreement

No hidden multipliers. No insider boosts.

**Open‑Source Components**
Where possible, Zuno releases:
- Client‑side app logic
- Task formatting specifications
- Consensus scoring logic

This allows independent verification of how tasks are processed 
and how rewards are calculated.

### 10.5 No Insider Advantage

Every token in circulation is earned through real work — completing 
AI data labelling tasks in the Zuno app. No hidden emissions, no 
early access to rewards, and no insider boosts of any kind.

### 10.6 Continuous Monitoring
The network continuously monitors:

- Abnormal task patterns
- Suspicious behaviour
- Repeated outlier outputs
- API abuse attempts
- Reward anomalies

Accounts that violate network rules are automatically rate‑limited or suspended.

---

## 11. Governance

### 11.1 Overview
ZUNO tokens grant holders governance rights over the Zuno Network. 
Every ZUNO token equals one vote. The more ZUNO a holder has earned 
through contributions, the greater their say in how the network 
evolves. Governance ensures the network remains community‑driven 
as it grows.

Reward rates, emission schedules, and treasury allocations are 
determined by community governance vote, not by the founding team.

### 11.2 What Token Holders Vote On
- Task reward emission rates
- Daily task cap adjustments
- Treasury spending and ecosystem grants
- Loyalty multiplier adjustments
- Protocol upgrades and new features
- Network partnership decisions

### 11.3 How Voting Works
- 1 ZUNO = 1 vote
- Simply holding ZUNO in your wallet gives you voting power
- No staking or lockups required to participate
- Proposals are submitted by community members
- A minimum threshold of ZUNO must be held to submit a proposal

Voting is conducted via Snapshot.org, a widely used off‑chain 
governance platform.

To vote:
1. Visit the official Zuno governance page on Snapshot.org
2. Connect your Solana‑compatible wallet
3. Your voting power is automatically calculated based on your 
   ZUNO balance
4. Browse open proposals and cast your vote

- No tokens are spent or locked — voting is free and non‑custodial
- All votes and results are permanently and publicly visible

Voting periods run for a fixed duration announced in advance via 
official Zuno channels.

### 11.4 Voting Phases
- **Phase 1** — Off‑chain voting via Snapshot. Votes are recorded 
  transparently but executed by the Zuno team. This keeps things 
  simple and cost‑free during early network growth.
- **Phase 2** — On‑chain governance introduced at launch. Votes 
  are executed automatically via smart contracts with no founder 
  intervention required.

### 11.5 Governance Principles
- No founder veto
- All proposals and results are publicly visible
- Voting periods run for a fixed duration announced in advance
- The founder holds 1% of total supply — ensuring no single party 
  can dominate votes or override the community

---

## 12. About the Founder

Stephen Tracey is a systems engineer and web developer with more than 20 years working across Government, Telecommunications and Healthcare — sectors where reliability, risk mitigation, data integrity and uptime are non‑negotiable. His background spans MSP ownership, enterprise IT management, ERP implementation, and hands‑on infrastructure work across some of Australia's most demanding environments.

After two decades of keeping critical systems stable, the same pattern kept appearing: AI was becoming more capable, but not more reliable. Incorrect outputs were slipping into reporting, analysis, and operational workflows — creating real risks around decisions, compliance, and legal liability.

Zuno Network was created to solve that problem at the foundation. By combining human validation with community-driven AI data labelling, Stephen designed Zuno as a system where accuracy is verifiable, not assumed — and where every token is earned through real work.


---

## 13. Conclusion

AI hallucination isn't a theoretical problem — it's happening today 
in every industry that relies on automated answers. When AI gets 
things wrong, the impact flows directly into decisions, reporting, 
legal liability, compliance, and trust.

Zuno Network exists to fix this at the foundation. Through 
community-driven AI data labelling, Zuno creates a continuous 
feedback loop where human judgement verifies accuracy at scale.

Anyone with a smartphone can contribute. Every token in circulation 
is earned through real work — completing AI data labelling tasks 
in the Zuno app.

As the network grows, so does the quality of its output. 
Community-verified data becomes the backbone for more reliable AI 
systems, and over time, forms the training ground for Zuno AI — 
a model built entirely on community‑validated truth.

A network built for accuracy, Powered by Humans, and anchored 
on Solana.

---

*© 2026 Zuno Network. Built on Solana.*

---

## Changelog

**v1.0 — May 2026 — Original release**
