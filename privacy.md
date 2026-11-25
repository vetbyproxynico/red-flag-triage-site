# Red Flag Triage: privacy policy

_Last updated: 25 November 2026_

Red Flag Triage is a Forge app for Jira Service Management, built by an individual developer as an entry to Atlassian Codegeist 2026. This policy explains what the app does with data on a site where it is installed.

## What the app processes
- **Ticket content:** the summary and description of tickets in the projects it triages, and of any text an agent asks it to preview.
- **Settings:** the project keys and options an administrator saves on the app's settings page.
- **Agree/override feedback:** the ticket key, the chosen category and the time. No user identifier is stored.

## Where processing happens
- All processing runs on **Atlassian's Forge platform**. Ticket text is analysed by Forge functions and by Claude models through **Atlassian's Forge LLMs** service, under Atlassian's terms.
- The app has **no servers of its own and sends no data outside Atlassian**. It declares no external network access.

## What the app stores, and where
- **Inside your Jira site:** a triage result as an issue property on each triaged ticket, `rft-*` labels, a priority change (raised only), and internal notes that customers cannot see. These stay in your site under your control. Removing the app does not remove them.
- **In Forge app storage for your site:** settings and agree/override feedback. These are deleted when the app is uninstalled, according to Forge's data deletion process.
- **In Forge logs**, which Atlassian keeps for a limited period: ticket keys, categories, token counts and errors. If the AI's reply fails, a log line can contain the start of that reply, which may quote the ticket.

The app **does not store personal data outside Jira and Atlassian's platform**, does not track users, and does not sell or share data.

## Your choices
- Administrators can limit which projects are triaged, turn off internal notes, or turn off AI calls entirely (safety rules only) on the app's settings page.
- Uninstalling the app stops all processing.

## Not a medical device
Red Flag Triage is decision support for software-support agents. It does not diagnose, treat or advise on the care of any patient.

## Contact
Use the support contact shown on the app's installation page.
