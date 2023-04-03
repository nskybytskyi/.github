# Security Policy

## Supported Versions

My recent and upcoming projects use [semantic versioning](https://semver.org/).

Within the same MAJOR version, only the most recent MINOR version  MAY be supported with security updates.

- The most recent MAJOR version SHALL be supported indefinitely.
- The previous MAJOR version:
  - SHALL be supported for at least 6 (six) months;
  - MAY be supported for up to 24 (twenty-four) months;

  since the release of the current MAJOR version.
- The less recent MAJOR versions SHALL NOT be supported.

### Example

The current version is 3.1.4, and a vulneravility is found. It also applies to most recent MINOR versions 2.7.1 and 1.y.z.
A PATCH 3.1.5 for the current version will be released. No PATCH for 3.0.z will be released. No PATCH for 1.y.z will be released.
- If 3.0 was released at most half a year ago, version 2 will get a security PATCH 2.7.2.
- If 3.0 was released at most two years ago, version 2 may get a security PATCH. I will take the dependants of 2.y.z in the consideration.
- If 3.0 was released over two years ago, version 2 will not get a security PATCH.


## Reporting a Vulnerability

Contact me at [n.skybytskyi@gmail.com](mailto:n.skybytskyi@gmail.com).
Use the bug report issue form as a template for your letter.

- If I accept your report, an appropriate security PATCH version SHALL be released within 1 (one) month.
  If I do not release a security PATCH within this period, you MAY disclose the vulnerability publicly in issues.
- If I decline your report, then it will not be addressed.
  You MAY disclose the supposed vulnerability publicly in issues to notify the dependants of old MAJOR versions.
- If I don't get back to you within 1 (one) month of you report, you MAY disclose the vulnerability publicly in issues.

Whenever publicly disclosing a vulnerability, make sure to consider all the implications, both for your projects and other dependants.
