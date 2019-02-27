# Rebooting the Web of Trust VIII: Barcelona (March 2019)

This repository contains documents related to RWOT8, the eighth
Rebooting the Web of Trust design workshop, which will run in
Barcelona, Spain on March 1st to 3rd, 2019. The goal of the workshop
was to generate five technical white papers and/or proposals on topics
decided by the group that would have the greatest impact on the
future.

Visit http://rwot8.eventbrite.com for more information and to purchase tickets.

[Event details for attendees (schedule, hotels, transportation) (pdf 14MB)](https://github.com/WebOfTrustInfo/website/welcome-pack/rwot8-barcelona-welcome-pack.pdf)

##  Topics & Advance Readings

In advance of the design workshop, all participants produced a one-or-two page topic paper to be shared with the other attendees on either:

* A specific problem that they wanted to solve with a web-of-trust solution, and why current solutions (PGP or CA-based PKI) can't address the problem?
* A specific solution related to the web-of-trust that you'd like others to use or contribute to?

**NOTE:** To add a paper, create a pull request to this repo with your contribution (preferably .md file or PDF), along with updates to the README.md here and in the Topics and Advanced Readings folder with a link to your paper and your name. Please also include a byline with contact information in the paper itself.

Here are the advanced readings to date:

### Primers

These primers overview major topics which are likely to be discussed
at the design workshop. If you read nothing else, read these. (But
really, read as much as you can!)

* [DID Primer](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/did-primer.md) — Decentralized Identifiers ([extended version](https://github.com/WebOfTrustInfo/rwot7-fall2018/blob/master/topics-and-advance-readings/did-primer-extended.md) also available)
* [Functional Identity Primer](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/functional-identity-primer.md) — A different way to look at identity
* [Verifiable Credentials Primer](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/verifiable-credentials-primer.md) — the project formerly known as Verifiable Claims

### Decentalized Identifiers (DID)
* [A DID for Every Thing: Driving Event Data Chain](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/A-DID-for-every-thing---Agile-Driving-Data-Chain.md)
  * by Carsten Stöcker and Michael Rüther
  * "Our broader objective is to establish a scalable digital twin protocol and a technology layer for autonomous things."
  * #verifiableclaims #reputation #IoT

* [Peer-Star Identity Manager](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/IdentityManager.md)
  * by André Cruz, João Santos, and Pedro Teixeira
  * "By using the application, users will be able to create identities on several DID methods, import identities created on other devices, manage Verifiable Claims of identities, authenticate to dApps (sessions)."
  * #VC #UX
  * [Specification](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/idm-spec.md)

* [DID Namespace Records](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/did-namespace-records.md)
  * by Drummond Reed
  * "Besides discoverability of different decentralized networks, DID namespace linking also enables building bridges between different governance frameworks and trust assurance models—key building blocks of a global web of trust."
  * #reputation

* [Peer-to-peer DIDs](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/P2P-DID.md)
  * by Brent Zundel
  * "Work on a DID Method spec for P2P DIDs as a special subset of DIDs that are not universally resolvable on some ledger or central storage infrastructure, but only within the group where they are used."
  * #ledgerless
  * [Specification](https://github.com/brentzundel/peer-did-method-spec)

* [Universal ID Framework](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/universal-id-framework.md)
  * by Shigeya Suzuki
  * "One of the ways to support references for multiple ID scheme everywhere is developing a general Universal ID Reference scheme, which covers not only the references to DID but also Distinguish Name-based scheme or possibly others."
  * #PKI

* [Identity Containers. Blockchain implementation proposal with DIDs & ERC725](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/identity-containers.md)
  * by Alex Puig
  * "Long story short, We suggest to store just a Merkle Root of the keys and claims being holded by an entity (user, organization..,) and set a list standard endpoints to query and interact between entities. This way most of the information is transferred off-chain and the whole system should be GDPR compliant."
  * #VC #ERC725 #DKPI #GDPR
  * [Full Proposal](https://gitlab.com/caelumlabs/sikaris)

* [Digital Trust Protocol](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/DigitalTrustProtocol.md)
  * by Carsten Keutmann and Tim Pastoor
  * "The Protocol allows anyone, including automated software, to issue their own cryptographic identities, for the use of trust and reputation and be able to verify those of others, without the need for a trusted third party. Users issue claims to other identities, and this way build a personal web of trust network."
  * #VC #DPKI #reputation

* [Current Status of the DID Specification](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/did-spec-current-status.md)
  * by Amy Guy and Dmitri Zagidulin

### General Self-Sovereign Identity
* [A Self-Sovereign Identity Framework/Thought Model proposal](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/SSI-FrameworkProposal.md)
  * by Rieks Joosten
  * "The SSIF provides a thought model and corresponding terminology that allows us to think in a precise manner about SSI within the context of its purpose(s) - which for us is the generic enablement of electronic support for (administrative) business transactions."
  * #commonlanguage
  * [Model](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/SSI-FrameworkProposal/SSI-FrameworkProposal.pdf)

### Identity Philosophy
* [On Interpersonal Data](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/on-interpersonal-data.md)
  * by Philip Sheldrake
  * "It turns out that there is very few data that may be described as purely personal data. That lunch date, that genome map, those photos, that joint bank account — all turn out to be interpersonal data."
  * #data #reputation

### Misc.
* [PSDAD - Data Format with Secure Semantics](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/psdad.md)
  * by Sandro Hawke
  * "Existing data serialization formats like JSON, JSON-LD, XML, and even ASN.1 (with its various encoding rules) work well enough for conventional computing environments, but they fall short when high levels of both trust and decentralization are required. PSDAD (plaintext self-describing assertional data) is a proposed new approach which uses natural language strings simultaneously as identifiers, delimiters, and documentation, resulting in a surprisingly simple and robust system with distinct advantages over known approaches in certain environments."
  * #data
  * [Specification](https://sandhawke.github.io/psdad/spec.html)

* [The Universal Ledger Agent: a Logical Result of Rabobank's Journey in Blockchain-based self-sovereign identity](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/universal-ledger-agent.md)
  * by David Lamers
  * "The universal ledger agent (ULA) is a component that is implemented by the app and the verifier. The ULA makes it possible to retrieve credentials from issuers, independently which standards and blockchain they use. Also, a verifier can accept and verify credentials from multiple standards."
  * #DID #VC #GDPR #ERC780

* [OIDC Profile for SSI](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/oidc-profile-for-ssi.md)
  * by Oliver Terbu and Andres Junge
  * "The goal is to continue the work on an OIDC profile for SSI based on [NS18] and [II18], and finalize the first version of it."
  * #VC

### Social Key Recovery
* [A New Approach to Social Key Recovery](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/social-key-recovery.md)
  * by Christopher Allen and Mark Friedenbach
  * "The goal of social key recovery is for the user to specify groups of individuals that together possess the ability to recover the root secret of a wallet."
  * #reputation #shamirsecretsharing #keymanagement

* [Security Considerations of Shamir's Secret Sharing](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/security_shamirs.md)
  * by Peg
  * "Issues with private key management often pose barriers to the adoption of empowering decentralised technologies and this is exactly what this project aims to address. ...
  Threshold-based secret sharing schemes provide a powerful tool to address the private-key custody problem. There are promising solutions to the issues explored in this article. However, we have focussed here mainly on technical limitations of such schemes."
  * #reputation #shamirsecretsharing #keymanagement


### UX and Use Cases
* [Digital Identity for the Homeless](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/Digital-Identity-for-the-Homeless.md)
  * by Mike Varley and Matthew Wong
  * "The focus of this topic is how to apply existing decentralized digital ID solution to help individuals experiencing homelessness in the city (Toronto). E.g. how to reserve services such as overnight shelters with digital ID, keep track of certificate offered by free public organized re-training programs, and built credibility via repeat use the the same digital ID with varies services run by non-profit organizations in the city etc."
  * #reputation

* [Designing an Educational Credentialing Ecosystem](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/educational-credentialing-ecosystem.md)
  * by Kim Hamilton Duffy, J. Philipp Schmidt, and Joe Andrieu
  * "One goal of this exercise was to understand whether (1) certain emerging SSI standards -- including Verifiable Credentials (VCs), Decentralized Identifiers (DIDs) -- and (2) blockchain anchoring are essential to the simplified digital verifiable credentialing system. If so, we wanted to trace them to specific requirements.
  An additional goal was defining a threat model, to understand which aspects could be handled by the system, and which must be addressed by other systems. ...
  Our concern is that an effective digital credentialing ecosystem would make fraud within an issuing organization more appealing, so our final goal of this paper is to raise awareness among the broader SSI community."
  * #DID #VC

* [Assist underrepresented groups when entering the labour market through self sovereign identity](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/diverse-teams.md)
  * by Karolin Siebert
  * "As a consequence of increasing migration we have workers educated by a wild mix of educational systems, this should not be limiting them from approaching and receiving positions that they actually would like to work in and would be suitable for. Official diplomas and certificates, proving previous studies and work experience, are not necessarily recognised, available in physical form or easily translatable in a certified manner. In addition to that and estimate of the World Bank states that 1 Billion of people are without a formal identity. Being assigned one would give them better access to the work market since just their physical presence and knowledge is not enough in many cases, but rather we require proof for education and experience."
  * #DID #VC


* [Where's the UX?](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/did-ux.md)
  * by Alberto Elias
  * "I've been doing some user testing with both developers and non-technical folks and every single one of them has complained about the authentication and registration flows. We all agree that this work is for nothing if people don't end up using them. This community is definitely human-focused, but initial DID implementations haven't nailed the user experience yet."
  * #DID #VC #socialkeyrecovery

* [Designing Identity for People & Places](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/identity-for-people-places.md)
  * by Venn Agency - Sam Chase, Joni McKervey, and Benji Miller
  * "This paper will explore how we may architect a more complete individual sovereignty via privacy and place identity as a person moves between private and public physical locations (home, transit, work etc). ​ By mapping our rights and reasonable expectations to privacy across different contexts and comparing with the rights of devices in our spaces, we’ll seek to outline systems of access and control that work in accordance with the rights and needs of both sides."
  * #DID #IoT

* [Journalistic use-cases for SSI: signatures, verified claims, and canonical-text registries](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/Journalistic%20use-cases%20for%20SSI:%20%20signatures%2C%20verified%20claims%2C%20and%20canonical-text%20registries)
  * by Juan Caballero and Jefferson Sofarelli
  * "Our long-term proposal is to design an SSI-platform-agnostic DID widget or middle-ware system for CMSs such that at the time of committing a canonical version of a published piece on a given publication's CMS, that canonical version could be hashed and signed, with signature and hash being stored in an immutable, external record against which the signature could later be checked (i.e., making a verifiable claim of authorship linking the article's original published form to a DID controlled by its author)."
  * #DID #VC #reputation


### Verifiable Claims (VC)
* [EU Digital Signature vs. VC Model](https://drive.google.com/file/d/1ehi0WMEJWNZV5Cx4wXsqPQC-wRcF4Zi2/view)
  * by L. Boldrin
  * "VC without ledger provides, as added value, subject confirmation and anonymity/pseudonimity support. VC with ledger provides, as a further value, VC revocation."
  * #digitalsignatures

* [How Do We Bootstrap the Web of Trust for VC](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/bootstrap_web-of-trust_reliance-lifecycle.md)
  * by Matt Stone and Dan Burnett
  * "In the world of Verifiable Credentials, it is essential that Verifiers can trust Issuers. To this end, there must be a common understanding of the 'functional identity' of the Issuer. How do humans establish the appropriate level understanding to trust the artifact with conviction? i.e. how does one link 'this key' to 'that real world entity (person, company, etc)'"
  * #DID #reputation
* [Multi-Factor Attribute Trust](https://github.com/wip-abramson/rwot8-barcelona/blob/master/topics-and-advance-readings/trusting-attributes.md)
  * By Will Abramson
  * "Developing flexible mechanisms for judging the trust of an attribute presentation is going to be essential to driving the network affects needed for widespread adoption of Verifiable Credential based identity networks."
  
  * [Minimal implementation of VCs for communities of practice on an agent-centric distributed platform](https://github.com/wip-abramson/rwot8-barcelona/blob/master/topics-and-advance-readings/vcs-agent-centric.md)
  * By Jakub Lanc
  * "Exploring suitability of agent-centric system implementations of Verifiable Credentials or Verifiable Credentials-like systems for use-cases from the distributed community of practice contexts."
  * #VC #reputation #education


### Specifications
* [The Multibase, Multihash, and Hashlink Specifications](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/multiformat-superfriends.md)
  * by Manu Sporny and Ganesh Annan

* [Multiformat Superfriends](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/multiformat-superfriends.md)

* [Current Status of the DID Specification](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/did-spec-current-status.md)
  * by Amy Guy and Dmitri Zagidulin

* [The Identity Manager Specification](https://github.com/WebOfTrustInfo/rwot8-barcelona/blob/master/topics-and-advance-readings/idm-spec.md)
  * by Adin Schmahmann, André Cruz, and Pedro Teixeira

* [Peer-to-peer DID Specification](https://github.com/brentzundel/peer-did-method-spec)
  * by Brent Zundel

* [PSDAD Specification](https://sandhawke.github.io/psdad/spec.html)
  * by Sandro Hawke
