# Steven Obiajulu

## CEO at UseJunior | Lawyer + Mechanical Engineer | MIT '13 + Harvard Law '18

I build open-source tools that help AI agents handle paperwork.

### About Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/steven-obiajulu)
[![open-agreements](https://img.shields.io/badge/open--agreements-4f46e5?style=for-the-badge&logo=github&logoColor=white)](https://github.com/open-agreements)
[![UseJunior](https://img.shields.io/badge/UseJunior-1f2937?style=for-the-badge&logo=rss&logoColor=white)](https://usejunior.com)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/stevenobiajulu)

### Professional Background

- CEO, UseJunior (2024-present) -- AI-powered contract review, SOC 2 Type II attested
- Associate Attorney, Ropes & Gray LLP (2019-2024)
- Technical Advisor, Ropes & Gray LLP (2013-2019)

### Projects

#### [open-agreements](https://github.com/open-agreements/open-agreements) ![GitHub stars](https://img.shields.io/github/stars/open-agreements/open-agreements?style=social)

25+ free legal agreement templates with DOCX output. NDAs, cloud service agreements, employment contracts, and more -- fill via CLI or API.

I'd welcome contributions -- if you're a practitioner who'd like to contribute templates, forms, or practice notes, email steven@usejunior.com.

#### [safe-docx](https://github.com/usejunior/safe-docx) ![GitHub stars](https://img.shields.io/github/stars/UseJunior/safe-docx?style=social)

Formatting-preserving DOCX edits for AI agents. Surgical text replacement that keeps styles, numbering, and tracked changes intact.

### Contributions to Other Projects

#### [xmldom](https://github.com/xmldom/xmldom)

- [#960](https://github.com/xmldom/xmldom/pull/960) -- Implemented the `ParentNode.children` getter. Shipped in [0.9.9](https://github.com/xmldom/xmldom/releases/tag/0.9.9).
- [#962](https://github.com/xmldom/xmldom/pull/962) -- Backported a regex fix to the 0.8.x branch so `ProcessingInstruction` data preserves trailing whitespace (XML spec §2.6).
- [#990](https://github.com/xmldom/xmldom/pull/990) -- Added accessors so direct assignment to `CharacterData.nodeValue` or `data` keeps both properties in sync; bug reported in [#989](https://github.com/xmldom/xmldom/issues/989). Merged April 18, 2026.

#### [bokuweb/docx-rs](https://github.com/bokuweb/docx-rs)

- [#879](https://github.com/bokuweb/docx-rs/pull/879) -- Added `MoveFrom`/`MoveTo` tracked-change support and updated `Paragraph::raw_text()` so moved text is not emitted twice. Merged April 22, 2026.

#### [NVIDIA/NemoClaw](https://github.com/NVIDIA/NemoClaw)

- [#1478](https://github.com/NVIDIA/NemoClaw/pull/1478) -- Added PATCH support to the Outlook preset so agents can update drafts and message state via Microsoft Graph; gap documented in [#1477](https://github.com/NVIDIA/NemoClaw/issues/1477). Merged April 23, 2026.

#### [WHATWG DOM Standard](https://github.com/whatwg/dom)

- [#1452](https://github.com/whatwg/dom/pull/1452) -- Reordered steps in `Range.deleteContents()` and `extractContents()` to collapse the range before removals, addressing [#1446](https://github.com/whatwg/dom/issues/1446). Merged March 2026.

### Speaking and Writing

- **Accord Project** (Linux Foundation, DocuSign-backed) -- AI-native legal infrastructure ([recording](https://vimeo.com/1179221957), April 2026)
- **Harvard Club of NYC** -- AI in Legal Practice (March 2026)
- **National Bar Association Conference**, Managing Partners Dinner -- UseJunior presentation
- **Ropes & Gray Alumni Podcast** -- [conversation with Ed Black, former Head of AI Strategy](https://www.ropesgray.com/en/insights/podcasts/2025/09/alumni-ropestalk-conversation-with-steven-obiajulu-usejunior) on UseJunior and AI adoption in legal workflows (September 2025)

### Education

- **Harvard Law School**, Juris Doctor (2015-2018)
- **MIT**, SB Mechanical Engineering (2009-2013)


---

### Cryptographic identity

This account, [UseJunior](https://github.com/UseJunior), and [open-agreements](https://github.com/open-agreements) all share a single Ed25519 key as a cross-domain identity binding:

- **Key ID**: `ed25519:e88cad0abc1ecf1b`
- **Public key**: [`usejunior.com/.well-known/arp/pubkey.json`](https://usejunior.com/.well-known/arp/pubkey.json)
- **DNS-anchored** at `arp._arp.usejunior.com` (also `arp._arp.openagreements.org` and `arp._arp.openagreements.ai`)
- **Registered as a GitHub SSH signing key** on this account; the same key signs every commit on this profile.

This is an experimental local profile inspired by IETF [draft-deforth-arp-00](https://datatracker.ietf.org/doc/draft-deforth-arp/) (Agentic Reasoning Protocol).
