# Five-minute paper research scheduler

This public repository contains only the scheduling workflow and this README.
Strategy source, model weights, news records and the single RM10,000 paper
account remain in a separate private repository. No financial account is connected.

Standard GitHub-hosted runners in public repositories are free. Scheduled runs
are best effort: five minutes is the intended frequency, not a delivery promise.
Yahoo minute bars may be delayed or unavailable. Stale quotes never authorize
new paper entries. This is a software research simulation, not live trading.

Only regular market windows are monitored. The private application checks
exchange calendars, Malaysia's lunch break and completed five-minute bars.
The encrypted deploy key is scoped to the private repository. Telegram secrets
remain in that private repository; notifications run there after persisted events.
Private accounting logs are not uploaded as public Actions artifacts.

Dependency caches contain third-party packages and the public FinBERT weights,
not strategy source, credentials, account files or private logs.

Daily training and summaries remain in the private repository. Intraday models
must pass chronological validation, alongside the existing daily price/news gate,
before any paper entry. A failing model means staying in cash.
