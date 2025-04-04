---

marp: true
theme: default
paginate: true
--------------

# Assessment presentation for the position of Product manager - Statecraft.tech

*by Fedor Shmorgilov*

---

# Industry trends

 - Massive internet adoption in last 30 years provokes demand for transparency
 - Composable governance stacks are rising (e.g. Aragon OSx, Zodiac, Moloch V3)
 - ZK Tools like MACI, zkVoting, and Semaphore are gaining interest
 - Governance systems without privacy are seen as intransparent or outdated
 - Groups need robust, formal governance tools — not just voting widgets — inspired by Balaji's vision
 - Governance fatigue in web3 communities is real - that increases demand for Product-led governance

---

# Potential User Base

- **Non-Profit Organizations**: Transparent and accountable governance structures for collaborative decision-making
- **Government Structures**: Civic engagement platforms with secure, verifiable voting and adaptable governance modules
- **Web3 Communities & DAOs**: Especially those requiring complex structure and customizable frameworks but lacking technical resources
- **Universities & Research Institutes**: To manage funding, research projects, or decentralized academic governance
- **Online Movements & Advocacy Networks**: To run consensus-driven campaigns or delegate representation

---

# Problems to be Solved

- Most DAO tools lack flexibility beyond basic token voting and a single voting mechanism
- Most DAO constructors does not support complex org stracture entangled with other DAOs
- Existing off-chain platforms don’t support private, verifiable ballots
- No simple way to create checks and balances within DAOs
- DAO builders struggle to evolve governance beyond MVPs

---

# Solutions

- Governance-as-a-Service for both on-chain and off-chain communities
- Drag-and-drop model editor for flexible institution design
- Verifiable, private voting on public blockchains
- Use cases span DAOs, online communities, and civic projects
- Designed to support experimentation and legitimacy in Web3 governance

---

# Strategic Overview part 1/3

## ✅ TAM — Total Addressable Market

*All organizations globally that require structured governance.*
 - NGOs & Nonprofits: 10M+ worldwide
 - Governments: 200+ nation states, thousands of cities and municipalities
 - Web3 DAOs: ~25,000+ active DAO-like projects (and growing)
 - Universities / Academic Institutions: 30,000+ globally
 - Online Communities (Discord, Reddit, etc.): Millions with potential governance needs

TAM (Annual Market Size):
~$10–15B+ (based on DAO tooling, civic platforms, and SaaS for governance across sectors)

---

# Strategic Overview part 2/3

## ✅ SAM — Serviceable Available Market

*Organizations actively seeking digital governance tooling with some Web3 readiness.*
 - ~10,000 active DAOs and Web3 communities (DeFi, gaming, NFT, RWA)
 - ~500 civic or academic organizations exploring digital governance pilots
 - ~1,000 enterprise-level nonprofits or foundations with governance complexity

SAM (Annual Market Size):
~$500M–$1B (estimated based on governance SaaS, grants, Web3 tooling budgets)

---

# Strategic Overview part 3/3

## ✅ SOM — Serviceable Obtainable Market (Initial 3 years)

*The portion Statecraft can realistically capture through direct outreach, PLG, and partnerships.*
 - ~500–1,000 DAOs or orgs using Statecraft by Y3 (Depending on the target market)
 - Estimated revenue for B2C: ~$100/month average per DAO (Considering current DAO platform revenue)
 - Advanced/governance-heavy clients: up to $10K+/year

SOM Estimate (Annual Revenue Potential):
~$5M–$10M within 3 years

---

# Competitor Analysis

| Platform | Blockchain | Key Focus                            | How Statecraft Differentiates                     | Avg. Montly proposals |
| -------- | ---------- | ---------------------------------   | ---------------------------------------------------| -------- |
| Aragon   | ✅ On-Chain  | DAO templates, on-chain voting    | More modular, may support more voting mechanisms   |  ~ 100 - 2k        |
| Colony   | 🟡 Hybrid    | Task-focused rep-based governance | Focus on scalable civic-like structures            |   Unknown     |
| Snapshot | 🟡 Hybrid    | Gasless voting (off-chain)        | Offers on-chain, secret ballots                    |  ~ 1k - 10k        |
| Consul   | ❌ Off-chain | Civic engagement tools            | On-chain, more transparent                         |   Unknown       |

---

# Monetization Strategy

- **Token Sales**: Introduce a native utility token for accessing advanced governance modules, staking, and optional DAO participation incentives
- **B2B/G Sales**: Offer governance-as-a-service packages for protocol teams, platforms, and institutions needing structured digital governance tools
- **Paid Promotion**: Allow curated communities or DAOs to promote their governance spaces, proposal campaigns, or network-state initiatives


---

# SWOT Analysis 1/2

**Strengths**

- Modular, intuitive UI
- Private and verifiable voting
- Multi-role, customizable institutions
- Great technical engine that enables customization and repackaging to suit specific industry needs

**Weaknesses**

- Early adoption curve is steep
- Absence of integration with existing web3 ecosystem
- Complexity for non-technical users

---

# SWOT Analysis 2/2

**Opportunities**

- Rise of Network State discourse
- Technologies for building interconnected DAO structures like Aragon OSx are still in early stages so it is easier to obtain the large portion of the market segment.
- Regulatory-compliant DAO tooling demand

**Threats**

- Competing DAO frameworks
- Web3 adoption by general public remains low
- Legal ambiguity in global jurisdictions

---

# Risk Mitigation Strategy

- Provide similar functions that existing DAO provides but with simplified UX
- Integrate into existing web3 ecosystem and adopt emerging technologies
- Smart contract audits before releases
- Governance modules tested in isolated deployments
- Advisory board across legal, civic tech, and protocol sectors

---

# Distribution Strategy

- **Strategic Partnerships**: Collaborate with DAO infrastructure providers, L2 networks, and civic tech platforms to expand reach and credibility
- **Content-Led Growth**: Offer educational resources such as guides, tutorials, webinars, and simulations targeted at DAO builders and community leaders
- **Product-led Growth**: Free-to-use governance templates and sandbox environments, viral loops through publicly visible governance setups
- **Ambassador Program**: Mobilize early adopters and power users to promote adoption across global DAO ecosystems

---

# Hypotheses part 1/2

Large-scale

- Offer preset templates that matches standard defi protocol to compete with existing DAO creation tools.
- Initial deployment of the a state on testnets such as Sepolia
- Deploy different governances on different chain - permissioned and permissionless.
- Allow various methods for voting like multisignature and token-based mechanisms
- Adopt account and chain abstraction to increase adoption
- Adopt gasless fees to reduce entry barrier for end users
- Create ways for State creators to promote their states

---

# Hypotheses part 2/2

Small-scale

- Add signup with metamask and other wallets to reduce entry barrier
- View transactions on blockchain explorer to increase adoption in web3 communities
- Visual timelines of decision history
- Add voting analytics
- Add veto mechanism between different entities

**All hypotheses mentioned above require heavy customer study (surveys, interviews, BD activity, etc.) before execution**

---

# Project Resource Allocation

Core team composition: 
 - Protocol engineers 
 - Backend engineers
 - Frontend engineers 
 - QAs 
 - Product designers
 - Governance research analyst

---

# Project Management

Scrum framework before production, Kanban after
 - Designers and protocol analyst working 1 sprint ahead
 - Frontend, backend, QA's working on 2-week sprint basis
 - Protocol engineers working in separate process, involving audit

---

# Roadmap (next three months)
| Feature                          | Reach  | Impact | Confidence | Effort | RICE Score  | Month     |
|----------------------------------|--------|--------|------------|--------|-------------|---------- |
| Wallet-based onboarding          | 8      | 8      | 9          | 3      | 192.0       | Month 1   |
| Blockchain explorer visibility   | 7      | 6      | 7          | 3      | 98.0        | Month 1   |
| Testnet deployment on Sepolia    | 6      | 6      | 8          | 3      | 96.0        | Month 1-2 |
| Gas-less transaction             | 9      | 8      | 6          | 9      | 48          | Month 2-3 |


---

# Assumptions

- Growing demand for complex structured governance
- DAOs will evolve toward structured legitimacy
- Users will demand both privacy and verifiability and a bit more willing to sacrifice UX for it
- Web3 adoption will continue to increase
- Governance participation demand will continue to increase
- Audit team is heavily involved and maintances constant effort`

---

# By Fedor Shmorgilov