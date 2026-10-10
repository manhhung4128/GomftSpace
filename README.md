<h1 align="center">GoMFT AI</h1>
<h3 align="center">AI-assisted managed file transfer for small IT teams</h3>

<p align="center">
  Schedule transfers between servers, SFTP and cloud storage. Watch every run in one place.<br>
  Let Claude explain what went wrong and suggest safe fixes.
</p>

<p align="center"><a href="https://gomft.space"><strong>gomft.space</strong></a></p>

> [!IMPORTANT]
> **Status: early stage.** The transfer features below are available today. The Claude features are **in development and not released yet**. There are no customers, users or usage numbers to report yet, and none are claimed.

## The problem

A nightly transfer fails with a short, cryptic error. Someone has to read the logs, work out whether it is a token, a path or a permission, and guess at a fix. For a small IT team this happens often, and it eats hours.

## What GoMFT AI does

### Claude, with guardrails (in development)

| Feature | Status | What you get |
|---|---|---|
| **Explain failures** | First feature in development | Claude reads the redacted log of a failed run, explains the likely cause in plain language and lists the checks to try, in order. |
| **Safe fix proposals** | Planned | Claude proposes a fix and shows its impact and risk. A person confirms before any important action. |
| **Workflows from plain language** | Planned | Say "move new CSV files from SFTP to S3 every night". Claude drafts the workflow and the app validates it before you confirm. |

**Safety by design**

- Claude recommends. You decide. It never deletes, overwrites or changes access permissions by itself.
- Passwords, tokens and keys are removed from logs before anything is sent to Claude.
- Every proposed workflow is validated before it can be saved.
- Sensitive operations always need human approval, and the impact is shown first.
- AI features are optional. File transfers never depend on Claude.

### Transfer management (available today)

- **30+ storage services:** Google Drive, Amazon S3, MinIO, NextCloud, WebDAV, SFTP, FTP, SMB, Backblaze B2, Wasabi and more.
- **Scheduling:** run transfers on a schedule with a visual schedule builder.
- **Monitoring:** live status, detailed run history, bytes and files transferred.
- **File history:** search and filter every transferred file for audit and compliance.
- **Fast transfers:** several files at once, file pattern filters, dated output names, archive after transfer.
- **Notifications:** email, webhooks, Pushbullet, Ntfy, Gotify and Pushover.
- **Teams and access:** roles and permissions, single sign-on, two-factor sign-in, audit log.
- **Admin tools:** live log viewer, backup and restore, system stats.
- **Light and dark mode.**

## Plans

| | **Free** | **Team** (planned, $29 / month) | **Business** |
|---|---|---|---|
| Scheduled transfers, monitoring, file history | ✓ | ✓ | ✓ |
| Roles, SSO, two-factor, audit log | ✓ | ✓ | ✓ |
| Claude failure explanations | | ✓ | ✓ |
| Safe fix proposals | | ✓ | ✓ |
| Workflows from plain language | | | ✓ |
| Support | Community | Email | Priority |

Paid plans are **not on sale yet** and prices may change before launch. To join early access, email [contact@gomft.space](mailto:contact@gomft.space?subject=GoMFT%20AI%20early%20access).

## Roadmap

| Phase | Goal |
|---|---|
| Now | Talk to small IT teams about their most time-consuming transfer problems. |
| Next | Release failure explanations to a small group of early users. |
| Then | Measure accuracy, time saved and cost. Add safe fix proposals. |
| Later | Workflows from plain language, based on feedback. |

We will publish results only when we have measured them.

## Contact

[contact@gomft.space](mailto:contact@gomft.space) · [gomft.space](https://gomft.space)

Claude is a trademark of Anthropic. GoMFT AI is not affiliated with Anthropic.
