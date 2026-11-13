# Security Policy

This policy applies to all repositories of the [sabre-io](https://github.com/sabre-io)
organization that do not ship their own `SECURITY.md`. Baïkal has its own policy, see
[sabre-io/Baikal](https://github.com/sabre-io/Baikal/security/policy).

## Reporting a vulnerability

**Please do not report security vulnerabilities through public GitHub issues,
pull requests or discussions.**

Instead, report them privately through GitHub's private vulnerability reporting:

1. Open the affected repository on GitHub, e.g. `https://github.com/sabre-io/dav`.
2. Go to the **Security** tab and click **Report a vulnerability**,
   or open `https://github.com/sabre-io/<repository>/security/advisories/new` directly.

Only the maintainers can see your report. We can discuss it with you, work on a
fix in a private fork, and publish a GitHub Security Advisory (and request a CVE)
from there.

### What to include

To help us triage your report quickly, please include as much of the following as you can:

- the affected package (e.g. `sabre/dav`, `sabre/vobject`) and version(s)
- the type of issue (e.g. XXE, path traversal, authentication bypass, XSS)
- the affected source file(s) or component, if known
- step-by-step instructions or a proof of concept to reproduce the issue
- the impact: what an attacker could achieve

## Supported versions

Security fixes are made for the latest release line of each package only
(for example sabre/dav 4.x). Please make sure the issue can be reproduced
against the latest release or the default branch.

## Our process

The sabre projects are maintained by volunteers, so all timelines are best effort.
We aim to:

1. acknowledge your report,
2. confirm the issue and decide on its severity,
3. prepare and release a fix,
4. publish a security advisory, crediting you unless you prefer otherwise.

Please give us a reasonable amount of time to release a fix before disclosing
the issue publicly.
