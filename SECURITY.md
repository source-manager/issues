# Security policy

SourceManager holds forge tokens, AI keys and keychain entries, so please report
vulnerabilities **privately**.

Use [Report a vulnerability](https://github.com/source-manager/issues/security/advisories/new)
on this repository. Do not open a public issue, and do not paste tokens, keys or
the contents of your log into one — the log records repository paths.

Include the release and build from **About > Copy details**, your platform, and
the steps to reproduce. You will get an acknowledgement as soon as it is read.

In scope: credential handling, what may leave the machine (forge, AI, ticket
requests), command or argument injection through the programs the app runs
(`git`, `gpg`, `ssh-keygen`, your editor and terminal), and the licence check.
