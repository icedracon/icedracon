<p align="center">
  <img src="assets/profile-command-center.svg" alt="icedracon command center: discover, map, validate, ship" width="100%" />
</p>

<h1 align="center">icedracon</h1>

<p align="center">
  <strong>Security research for Windows identity.</strong><br />
  <sub>Evidence-first Active Directory assessment · Windows authentication research · transparent Rust protocol tooling</sub>
</p>

<p align="center">
  <a href="https://github.com/icedracon/adhammer"><img src="https://img.shields.io/badge/ADHAMMER-EXPLORE-2EA8FF?style=flat-square&labelColor=03060C" alt="Explore ADhammer" /></a>
  <a href="https://icedracon.github.io/adhammer/"><img src="https://img.shields.io/badge/PROJECT%20SITE-OPEN-A78BFA?style=flat-square&labelColor=03060C" alt="Open the ADhammer project site" /></a>
  <a href="https://github.com/icedracon?tab=repositories"><img src="https://img.shields.io/badge/ALL%20CODE-GITHUB-55D6BE?style=flat-square&labelColor=03060C" alt="Explore all icedracon repositories" /></a>
</p>

## What I build

I build evidence-first security tools for authorized Active Directory assessment.
I research Windows authentication and create small, inspectable Rust protocol
foundations with reproducible results and safe parsing.

<p>
  <img src="https://img.shields.io/badge/01%20DISCOVER-AD%20POSTURE-2EA8FF?style=flat-square&labelColor=03060C" alt="Discover: Active Directory posture" />
  <img src="https://img.shields.io/badge/02%20MAP-IDENTITY%20PROTOCOLS-A78BFA?style=flat-square&labelColor=03060C" alt="Map: identity protocols" />
  <img src="https://img.shields.io/badge/03%20VALIDATE-REPRODUCIBLE%20EVIDENCE-F7C948?style=flat-square&labelColor=03060C" alt="Validate: reproducible evidence" />
  <img src="https://img.shields.io/badge/04%20SHIP-OPEN%20RUST%20TOOLING-55D6BE?style=flat-square&labelColor=03060C" alt="Ship: open Rust tooling" />
</p>

## Selected work

- [**ADhammer**](https://github.com/icedracon/adhammer) — evidence-first Active
  Directory assessment: collect scoped signal, map Tier-0 control paths, and
  keep supported proof connected to the report. [Project site](https://icedracon.github.io/adhammer/) · [Latest release](https://github.com/icedracon/adhammer/releases)
- [**dcerpc**](https://github.com/icedracon/dcerpc) — Rust DCE/RPC protocol work.
- [**ntlmssp**](https://github.com/icedracon/ntlmssp) — NTLMSSP / NTLMv2 protocol work.
- [**ms-ndr**](https://github.com/icedracon/ms-ndr) — safe NDR parsing work.

## Research areas

<details>
<summary><strong>Open the research map</strong></summary>
<br />

- **Windows identity** — Active Directory, Kerberos, NTLMSSP, LDAP, SMB,
  DCE/RPC, NDR, DPAPI-NG, WinRM, and CredSSP.
- **Defensive evidence** — SIEM-oriented handoff, monitoring, log analysis,
  incident reporting, and transparent validation.
- **Adjacent defensive research** — Sigma/YARA detection work plus EDR and DLP
  awareness. These are external controls, not claims about a single tool.
- **Assessment boundaries** — Active Directory assessment is the native focus;
  web and Android / APK testing are separate, explicitly scoped disciplines.
- **Engineering** — pure Rust protocol implementation, authentication protocol
  work, safe binary parsing, and reproducible open-source tooling.

</details>

## Working principles

- Make the scope visible before an assessment starts.
- Treat an observed condition and a proved condition as different things.
- Build tools that are inspectable, reproducible, and useful to defenders.

<p>
  <img src="https://img.shields.io/badge/SCOPE-AUTHORIZED%20RESEARCH%20ONLY-FB7185?style=flat-square&labelColor=03060C" alt="Scope: authorized research only" />
</p>

Security research and assessment work is for systems I own or am explicitly
authorized to test. The goal is transparent validation and stronger defensive
decisions.
