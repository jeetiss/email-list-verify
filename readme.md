# Email-list-verify

<a href="https://uploadcare.com/?utm_source=github&utm_campaign=email-list-verify">
    <img align="right" width="64" height="64"
         src="https://ucarecdn.com/2f4864b7-ed0e-4411-965b-8148623aa680/uploadcare-logo-mark.svg"
         alt="">
</a>

Verify every email in file

[![Uploadcare stack on StackShare][badge-stack-img]][badge-stack-url]

<!-- toc -->

- [Requirements](#requirements)
- [Install](#install)
- [CLI Usage](#cli-usage)
- [Security issues](#security-issues)
- [Feedback](#feedback)
- [Authors](#authors)

<!-- tocstop -->

<!-- Long description. -->

## Requirements

node and npm

## Install

```bash
npm i -g @uploadcare/email-list-verify
```

or

```bash
yarn add global @uploadcare/email-list-verify
```

## CLI Usage

```bash
Usage

  $ email-list-verify -o mails.csv mails-to-test.csv
  $ email-list-verify -c 50 mails.csv
  $ email-list-verify --help

Options

  --file file                The input file with emails.
  -o, --output file          The output file.
  -c, --concurrency number   Concurrency.
  -h, --help                 Print this usage guide.
```

## Security issues

If you think you ran into something in Uploadcare libraries which might have
security implications, please hit us up at [bugbounty@uploadcare.com][uc-email-bounty]
or Hackerone.

We'll contact you personally in a short time to fix an issue through co-op and
prior to any public disclosure.

## Feedback

Issues and PRs are welcome. You can provide your feedback or drop us a support
request at [hello@uploadcare.com][uc-email-hello].

## Authors

- [Elijah][dayton-link] — idea, readme
- [Dmitry Ivakhnenko][jeetiss-link] — code
- [Siarhei Bautrukevich][bautrukevich-link] — review

[badge-stack-img]: https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat
[badge-stack-url]: https://stackshare.io/uploadcare/stacks/
[uc-email-bounty]: mailto:bugbounty@uploadcare.com
[uc-email-hello]: mailto:hello@uploadcare.com
[jeetiss-link]: https://github.com/jeetiss
[dayton-link]: https://github.com/dayton1987
[bautrukevich-link]: https://github.com/bautrukevich
