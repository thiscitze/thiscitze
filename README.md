<p align="center">
  <img src="banner.svg" alt="thiscitze — security research" width="100%">
</p>

**Security research · PoC + exploit development**
WordPress · Linux · kernel

---

### CVEs

| CVE | Target | Impact | CVSS |
|---|---|---|---|
| [CVE-2026-118423](https://github.com/thiscitze/cve-2026-118423-poc) | WP Libre Form ≤ 1.5.0.1 | Unauthenticated upload → RCE | 10.0 |
| [CVE-2026-113615](https://github.com/thiscitze/cve-2026-113615-poc) | GS JWT ≤ 1.0.0 | Unauthenticated SQLi → admin JWT | 9.8 |
| [CVE-2026-100109](https://github.com/thiscitze/cve-2026-100109-poc) | Security For WooCommerce 1.0.10–1.0.16 | Unauthenticated admin creation | 9.8 |
| [CVE-2026-114630](https://github.com/thiscitze/cve-2026-114630-poc) | ELEX HelpDesk ≤ 3.3.8 | Unauthenticated arbitrary file deletion | 9.1 |
| [CVE-2026-41651](https://github.com/thiscitze/cve-2026-41651-poc) | PackageKit 1.0.2–1.3.4 | TOCTOU local privilege escalation | — |
| [CVE-2026-74580](https://github.com/thiscitze/cve-2026-74580-poc) | Linux vhost | vring metadata cache LPE (maintained fork) | — |
| [CVE-2026-86596](https://github.com/thiscitze/cve-2026-86596-poc) | s2Member ≤ 260927 | Template injection (lab) | — |
| [CVE-2026-98432](https://github.com/thiscitze/cve-2026-98432-root-shell) | Linux IPv4/TCP | Lab root-shell kit | — |

### Tools

| Project | What it does |
|---|---|
| [autoroot](https://github.com/thiscitze/autoroot) | One-command Linux privilege-escalation runner for disposable VMs |

### Policy

Authorized testing only. Every PoC targets a documented vulnerability and ships without live target data.

[X](https://x.com/thiscitze) · [GitHub](https://github.com/thiscitze)
