+++
title = "The Fall of the Cyber Guardians"
date = 2026-03-11
slug = "the-fall-of-the-cyber-guardians"
tags = ["security", "governance", "risk", "geopolitics"]
description = "NIST and CISA gave us the frameworks we built our programmes on. Now they're being gutted — and no one in the industry is saying a word."
+++

For twenty years, two US agencies shaped how the rest of the world thought about cybersecurity. NIST gave us a risk management framework that was logical, legible, and sensible enough that governments from Canberra to Copenhagen adopted it — or built their own in its image. CISA became the authoritative voice on critical infrastructure protection, vulnerability management, and incident response. Between them, they set the standard. Literally.

That's over now.

## What's happened

Since January 2025, both agencies have been systematically dismantled under the banner of "government efficiency." CISA has lost roughly a third of its workforce — around a thousand people — through layoffs, forced resignations, and the elimination of entire programmes including election security and counter-ransomware operations.[^1] The proposed FY2026 budget would cut its workforce from 3,732 to 2,649 positions — a reduction of nearly 30%.[^2]

NIST has shed more than 700 jobs, including 89 at the lab responsible for validating government encryption.[^3] The same lab standardising post-quantum cryptographic algorithms — arguably the most consequential cryptographic transition in decades — is now understaffed and losing institutional knowledge. The National Vulnerability Database, which the entire global security industry depends on for vulnerability intelligence, has been drowning in a processing backlog since 2024 and is now losing the people who might have fixed it.[^4]

These aren't political appointees. They're career cryptographers, incident responders, framework authors, and vulnerability analysts. The kind of people who take decades to develop and can't be replaced by a contractor with a Jira board.

## The silence

What's striking is who isn't saying anything.

Jackie Singh wrote about this in her piece for *Hacking, But Legal* — that the cybersecurity industry, an industry that markets itself on courage and adversarial thinking, has gone completely quiet.[^5] Reuters contacted 33 of the largest US cybersecurity companies for comment on the targeting of former CISA director Chris Krebs. Thirty-two either declined or didn't respond.[^6]

Krebs — who built CISA and was fired for publicly stating that the 2020 election was secure — had his security clearance revoked by executive order in April 2025. The same order suspended clearances for every employee at SentinelOne, the company he worked for. He resigned shortly after.[^7] The message was clear: cross us and we'll go after your employer too.

And the industry heard it. They heard it and they shut up.

## Why this matters here

I run an information security programme in Australia. My frameworks, my risk registers, my control libraries — they all trace their lineage back to NIST and CISA guidance. The Essential Eight, the ISM, the VPDSF — they draw from the same well. When that well is poisoned, we feel it, even if we pretend we don't.

But there's a more immediate problem. We are deeply dependent on US-based service providers. Microsoft holds our email, our identity, our collaboration platforms. AWS and Azure run our infrastructure. We use American AI models, American SaaS platforms, American threat intelligence feeds. Every one of those companies operates under the CLOUD Act, which allows US law enforcement to compel disclosure of data stored anywhere in the world — including data belonging to Australian citizens and government agencies.[^8]

That was a manageable risk when the US government was broadly aligned with the rule of law and its own institutional norms. It's a different calculation entirely when the same government is using executive orders to punish private companies for the political views of their employees, when DOGE operatives are downloading sensitive personal data from across federal agencies with no legal authority and no audit trail,[^9] and when a federal judge has warned that Treasury Department data may have already been shared in violation of federal law.[^10]

The EU has noticed. Spending on sovereign cloud infrastructure is projected to triple to US$23 billion by 2027.[^11] France and Germany launched a joint summit on European digital sovereignty in November 2025, with a task force reporting in 2026.[^12]

Australia, meanwhile, is still largely pretending this is someone else's problem.

## The uncomfortable question

Here's where I wrestle with something professionally uncomfortable. We teach risk practitioners — I am one — to balance the cost of a mitigation against the consequence of a risk being realised. It's rational. It's sensible. It's in every certification curriculum I've ever studied.

But what happens when the consequence of a breach is functionally zero?

Fines in Australia for data breaches remain laughable compared to the EU's GDPR regime or even the US regulatory environment. If a US-based service provider mishandles Australian data, what exactly happens? What leverage do we have? If the provider is simultaneously being compelled by its own government to hand over that data, who do we complain to?

We spend enormous effort building risk frameworks, writing policies, conducting assessments, and maintaining controls — all predicated on the assumption that there's a functioning ecosystem of standards bodies, enforcement mechanisms, and consequences. When NIST is gutted, when CISA is hollowed out, when the US government itself is the threat actor raiding its own databases, that ecosystem is broken.

And the question that no one in our profession wants to ask is: are we just going through the motions?

I don't think we are. I think the work still matters, because the threats haven't gone away — they've multiplied. But I think we need to be honest about the fact that the foundations we built on are shifting, and that the assumption of a stable, trustworthy US-led cybersecurity ecosystem is no longer safe.

The frameworks were always tools, not scripture. It's time we started treating them that way — and started building the ones we actually control.

---

[^1]: Axios, "[One-third of U.S. cyber agency CISA has left since Trump took office](https://www.axios.com/2025/06/03/cisa-staff-layoffs-resignations-trump-cuts)," June 2025.

[^2]: Nextgov/FCW, "[CISA projected to lose a third of its workforce under Trump's 2026 budget](https://www.nextgov.com/cybersecurity/2025/06/cisa-projected-lose-third-its-workforce-under-trumps-2026-budget/405726/)," June 2025.

[^3]: CyberScoop, "[NIST officials detail impact of staff cuts on encryption and other priorities](https://cyberscoop.com/encryption-nist-officials-detail-staff-cuts-impact/)," 2025.

[^4]: Foundation for Defense of Democracies, "[Cutting NIST's Workforce Threatens American Tech Innovation and Leadership](https://www.fdd.org/analysis/2025/04/16/cutting-nists-workforce-threatens-american-tech-innovation-and-leadership/)," April 2025.

[^5]: Jackie Singh, "[The Industry That Fights Governments for a Living Won't Fight This One](https://www.hackingbutlegal.com/p/the-industry-that-fights-governments)," *Hacking, But Legal*, 2025.

[^6]: NBC News, "[U.S. cyber defenders shaken by Trump's attack on their former boss](https://www.nbcnews.com/tech/security/us-cyber-defenders-shaken-trumps-attack-former-boss-rcna200597)," 2025.

[^7]: CNBC, "[Former cybersecurity agency chief Chris Krebs leaves SentinelOne after Trump targets him in executive order](https://www.cnbc.com/2025/04/16/former-cisa-chief-krebs-leaves-sentinelone-after-trump-exec-order.html)," April 2025.

[^8]: Australian Government Department of Home Affairs, "[Australia-US CLOUD Act Agreement](https://www.homeaffairs.gov.au/about-us/our-portfolios/national-security/lawful-access-telecommunications/australia-united-states-cloud-act-agreement)."

[^9]: NPR, "[The government already knows a lot about you. DOGE is trying to access all of it](https://www.npr.org/2025/03/11/nx-s1-5305054/doge-elon-musk-security-data-information-privacy)," March 2025.

[^10]: NPR, "[Federal judge blocks DOGE from accessing sensitive U.S. Treasury Department material](https://www.npr.org/2025/02/08/g-s1-47350/states-sue-to-stop-doge-accessing-personal-data)," February 2025.

[^11]: Data Center Dynamics, "[Europe spending on sovereign cloud infrastructure to triple from 2025-2027 — Gartner](https://www.datacenterdynamics.com/en/news/europe-spending-on-sovereign-cloud-infrastructure-to-triple-from-2025-2027-gartner/)," 2025.

[^12]: CNBC, "[Europe bids for digital sovereignty amid Russia threats, Trump](https://www.cnbc.com/2026/02/18/europe-digital-sovereignty-geopolitical-tensions.html)," February 2026.
