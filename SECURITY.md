# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in Transf-ORM-CLI, please **do not** create a public GitHub issue. Instead, please report the vulnerability responsibly by contacting the maintainers directly.

### How to Report

1. **Email**: Send a detailed description of the vulnerability to the project maintainers
2. **Include the following information**:
   - Description of the vulnerability
   - Steps to reproduce (if possible)
   - Potential impact
   - Suggested fix (if you have one)

### Response Timeline

- **Initial response**: We aim to acknowledge your report within 48 hours
- **Investigation**: We will work to understand and assess the severity
- **Fix**: We will work on a fix and prepare a security update
- **Disclosure**: Once a fix is available, we will coordinate disclosure

## Supported Versions

We support security updates for the following versions:

| Version | Supported          | EOL Date   |
|---------|------------------|------------|
| 1.x     | :white_check_mark: | TBD        |

## Security Best Practices

When using Transf-ORM-CLI:

- Keep your Rust toolchain and dependencies up to date
- Review the security advisories for your dependencies regularly using `cargo audit`
- Follow the principle of least privilege when executing database operations
- Validate and sanitize user inputs before using them with this tool
- Use secure credentials management for database connections

## Known Issues

None currently reported.

## Security Scanning

We perform regular security scans using:

- `cargo audit` - for dependency vulnerabilities
- `gitleaks` - for secret detection
- GitHub's code scanning and dependency analysis

## Additional Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Rust Security Guidelines](https://anssi-fr.github.io/rust-guide/)
- [Database Security Best Practices](https://en.wikipedia.org/wiki/Database_security)

## Policy Updates

This security policy may be updated periodically. Please check back regularly for any changes.

Last updated: March 2026
