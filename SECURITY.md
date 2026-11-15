# SECURITY POLICY

## Scope
This policy applies to the `skygoose/php-console-tooltips` repository and its official releases. It does not apply to forks, unofficial builds, or third-party distributions.

## Supported Versions
Only the latest stable release and the `main` branch are actively supported for security fixes. Older versions are not patched.

| Version | Status |
|---------|--------|
| `main` | Supported |
| Latest Stable Tag | Supported |
| All Previous Tags | Unsupported |

## Reporting Vulnerabilities
Vulnerabilities must not be reported via public Issues or Pull Requests.

- **For GitHub:** Use the "Report a vulnerability" button in the Security tab.
- **For GitVerse / Other channels:** Email `zagorodneff.kirill@gmail.com` with subject `[SECURITY] php-console-tooltips`.

The report must include:
- A clear description of the issue and its impact.
- Steps to reproduce (minimal PoC).
- Environment details (PHP version, OS, terminal).

## Response and Disclosure
- Initial acknowledgment: within 72 hours.
- Severity assessment: within 7 days.
- Patch release: as soon as feasible; critical issues receive highest priority.

Disclosure to the public will occur only after a fix is released or coordinated with the reporter.

## Exclusions
The following are not considered security vulnerabilities:
- Issues caused by incorrect usage of the library by the consumer.
- Problems originating in dependencies (report to the dependency maintainer).
- Feature requests, documentation gaps, or style issues.
- Issues related to data storage or secret management by the application using this library.

## Contact
Maintainer: SkyGoose (Kirill Zagorodnev)
Email: <a href="mailto:zagorodneff.kirill@gmail.com">zagorodneff.kirill@gmail.com</a>
Repository (RU): <a href="https://gitverse.ru/skygoose/PHPConsoleTooltips">https://gitverse.ru/skygoose/PHPConsoleTooltips</a>
Repository (EN): <a href="https://github.com/is-skygoose/PHPConsoleTooltips">https://github.com/is-skygoose/PHPConsoleTooltips</a>
