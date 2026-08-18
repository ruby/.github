# Security Policy

This policy applies to the repositories in this organization: the Ruby
interpreter, the standard library, default and bundled gems, and the developer
tools maintained here.

日本語版は [ruby-lang.org のセキュリティページ](https://www.ruby-lang.org/ja/security/)
をご覧ください。

## How to report a vulnerability

Please use one of these two channels:

- **HackerOne** — <https://hackerone.com/ruby>
- **Email** — <security@ruby-lang.org>

You may encrypt your email. The PGP public key is at
<https://www.ruby-lang.org/security.asc>.

**Please do not open a public issue or a public pull request for a security
problem.** A public report tells everyone about the problem before a fix
exists. Use HackerOne or email instead.

This includes libraries that live in their own repository here. For example, a
problem in `ruby/openssl` or `ruby/psych` is a problem in Ruby, because those gems
ship with Ruby. Please report it through the channels above, not in the
library's issue tracker.

## What happens next

- The Ruby security team reviews your report.
- Valid problems are published after a fix is ready.
- Please read the scope notes on the [HackerOne program
  page](https://hackerone.com/ruby) before you report.

## Not covered by this policy

- **The website.** Report problems in <https://github.com/ruby/www.ruby-lang.org>.
- **Gems that are not part of Ruby.** Follow the [RubyGems.org security
  instructions](https://guides.rubygems.org/security/#reporting-security-vulnerabilities).

## More information

<https://www.ruby-lang.org/en/security/>
