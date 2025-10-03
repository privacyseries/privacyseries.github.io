---
draft: false
title: "Privacy and data protection in DLT: Standards development at the ISO and CEN/CLC"
date: 2025-10-03T00:00:00+08:00
---

##Introduction
Distributed Ledger Technology (DLT) has started to be deployed in broad array of domains, developing prominent roles in finance, trust services, art, and gaming. Europe has provided the Single Market with a robust regulatory framework for DLT, through the domain specific [Market in Crypto-Assets Regulation](https://eur-lex.europa.eu/eli/reg/2023/1114/oj) (MiCAR), and complementary regulations in the realms of finance (e.g., [Anti-money Laundering Regulation](https://eur-lex.europa.eu/eli/reg/2024/1624/oj), [MiFID 2](https://eur-lex.europa.eu/eli/dir/2014/65/oj), [Transfer of Funds Regulation](https://eur-lex.europa.eu/eli/reg/2023/1113/oj), etc), trust services (e.g., [eIDAS2](https://eur-lex.europa.eu/eli/reg/2024/1183/oj)), and data (e.g., [GDPR](https://eur-lex.europa.eu/eli/reg/2016/679/oj), [Data Act](https://eur-lex.europa.eu/eli/reg/2023/2854/oj), [Data Governance Act](https://eur-lex.europa.eu/eli/reg/2022/868/oj), etc). 

It seems clear that Europe is keen to adopt DLT, leveraging the technology’s characteristics for improved accountability, immutability, and security. 

However, after 15 years of the technology existing, data protection and privacy concerns are still unresolved – especially those related to the balancing of data protection requirements (such as those derived from GDPR), with financial transparency and accountability requirements such as those stemmed from MiCAR and the Anti-Money Laundering Regulation (AMLR).

This blog outlines the privacy and data protection focused work being done in standards development organisations: the International Standards Organization (ISO), as well as the European Committee for Standardization and the European Committee for Electrotechnical Standardization – together entitled ‘CEN/CLC’. It introduces the standards currently in development that will, hopefully, provide clarity for European and international DLT ecosystems, as actors attempt to navigate the complexities of balancing privacy, data protection, and accountability requirements across use-cases.

##Privacy, data protection, and the European DLT ecosystem
The European community has enshrined privacy and data protection into the [Charter of Fundamental Rights for the European Union](https://eur-lex.europa.eu/eli/treaty/char_2012/oj) through Articles 7 (privacy) and Article 8 (data protection). 

The European Commission further emphasises the importance of these rights in the digitisation of European society – whether through the [European Declaration of Digital Rights and Principles for the Digital Decade](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=OJ:JOC_2023_023_R_0001), or the [Communication on the European Strategy for Data](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:52020DC0066).

Since the birth of Bitcoin and the subsequent development of the DLT ecosystem, it has become common knowledge that certain types of DLT implementations have consequences for privacy and data protection. 

Previously, the ISO published a technical report [ISO/TR 23244:2020 Blockchain and distributed ledger technologies — Privacy and personally identifiable information protection considerations](https://www.iso.org/standard/75061.html). The report outlines current privacy and PII considerations for DLT systems but that project did not specify any guidance or requirements for capability assessment, technical improvement, or the preservation of privacy.

Some years later, technology has evolved, and specific privacy requirements (and technological limitations) have begun to surface, as deployers and developers attempt to understand the tradeoffs between privacy, security, decentralisation, and regulatory obligations concerning identifiability, accountability and attribution. 

##SDOs establishing privacy and data protection norms
Through the ISO, work is being done to standardise the deployment of privacy technologies in the DLT ecosystem. [ISO TS 24946 Requirements and guidance for improving, preserving, and assessing the privacy capability of DLT systems](https://www.iso.org/standard/88614.html) is a technical specification currently at the Committee Draft (CD1) stage. The project is housed within a Joint Technical Committee, entitled ISO/TC 307/JWG 4 "Joint ISO/TC 307 - ISO/IEC JTC 1/SC 27 WG: Security, privacy and identity for Blockchain and DLT". 

As the project moves through its development, it has evolved to become a rich source of information for the DLT ecosystem. It outlines complex facets of DLT systems, including topics such as identity claims, identity attribution, and the designation of roles and functions. It also outlines a host of technical measures for the improvement of privacy in DLT systems, detailing requirements and recommendations related to governance, policies, consensus mechanisms, infrastructure, and participants. 

ISO TS 24946 also provides an optional capability assessment tool, which allows entities to justify and communicate why certain technical design and development decisions were made regarding the privacy capabilities of the DLT system under assessment - aligning the DLT system’s privacy affordances with the regulatory environment whilst highlighting technical limitations, or domain specific user requirements. 

From a European perspective, CEN/CLC recently approved (March 2025) the creation of a new Working Group (WG), entitled “CEN/CLC JTC 19/WG 3 - Personal identifiable information (PII) in Blockchain and DLT”. This WG will harmonise (where possible) standardisation efforts at the international level with those in Europe. 

CEN/CLC JTC 19/WG 3 are currently producing a European standard on personal data protection within DLT, strongly influenced by [DIN Spec 4997 - Privacy by Blockchain Design](https://webstore.ansi.org/standards/din/dinspec49972020) and ISO TS 24946. Harmonisation between the international specification at ISO and the European standard will support interoperability and ensure that privacy and data protection capabilities are standardised globally.

##European data protection norms and societal impact
European standardisation objectives at the intersection of DLT, privacy, and data protection are detailed in the [Rolling Plan for ICT Standardisation 2025](https://interoperable-europe.ec.europa.eu/collection/rolling-plan-ict-standardisation/rolling-plan-2025). The EC Rolling plan acknowledges that privacy, and data protection by-design auditing, is a target, especially through distinct certification services. The work proposed within CEN/CLC/JTC19/WG3 is based on the concept of 'Privacy-by-Blockchain-Design', developed through the German standards authority DIN. Further elaboration of the methods, frameworks and assessment tools in the DIN 4997 specification will support wider privacy and security enhancements for Europe, impacting on the privacy afforded to wider European society. 

Developing a European standard for personal data protection in DLT systems will provide important technical and organisational requirements, and a capability assessment tool to support regulatory alignment. 

Currently, MiCAR and AMLR propose exacting compliance obligations on Crypto-Asset Service Providers (CASPs) regarding the issuance and offering of 'crypto-assets' that have "inbuilt anonymisation functions". Providing clarity on 'anonymity functions', their implementation in DLT systems, and the ways in which they can be assessed for their privacy, data protection, and security guarantees is integral for the European DLT ecosystem – especially as DLT deployers seek GDPR compliance as they enter the European market.

The work being completed might help clarify some of the existing uncertainty which has, ultimately, led to the delisting of some privacy-preserving assets from the European market. These privacy-preserving assets have been marginalised as regulatory pressure has been applied, with CASPs classifying some of the exact technologies detailed in international standards such as the aforementioned “ISO TR2344:2020” as too ‘high-risk’ for their specific AMLR related compliance objectives, even though the same technologies are considered key components of GDPR compliance, and specific technical measures required for robust data protection risk mitigation. 
##Towards regulatory alignment and international harmonisation
Exacting requirements such as those posed by Article 76(3) of MiCAR, on “inbuilt anonymisation functions” as well as Recital 160 and Article 79(1) of the European AMLR, on “anonymity-enhancing coins” require careful navigation. 

Properly harmonised standards require alignment and compatibility with the text of those regulations. Ensuring there are no gaps between regulatory texts and the proposed European standards should be a primary focus of the work being done within CEN/CLC/JTC19/WG3. Ensuring there are no gaps between international specifications and European standards should be a key supporting focus.

Guidance on assessing DLT privacy affordances will allow National Competent Authorities, Financial Investigation Units, and other national and European agencies to  assess and appraise (fairly and objectively) the risks associated with the offering of crypto-assets with “inbuilt anonymisation functions” which are not developed to afford criminal behaviour – but to afford the protection of fundamental rights regarding privacy and data protection to European (and international) consumers. 

The work is also directly related to the European Rolling Plan for ICT standardisation, "Action 5: SDOs to continue investigating technical measures apt to make personal data anonymous or pseudonymised (and therefore unintelligible by those who are not authorised to access them)."

##Conclusion
Harmonisation efforts at the international level (through ISO TS 24946) will support global interoperability and ensure that European expectations and norms are represented fairly. Experts working in parallel through CEN/CLC/JTC19/WG3 and ISO/JWG4 will ensure coherence, with more fairly represented consensus discussions being reached on key topics. Stronger collaboration between European and international interests in the DLT ecosystem will try to ensure that the privacy and data protection harms we currently see in the vast majority of DLT systems, do not propagate further than is necessary, with the required risk mitigation tools, and technologies, being developed, supported, and recommended across DLT’s target domains, impacting European, and global, society for the better.
